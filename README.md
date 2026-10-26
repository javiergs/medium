# Medium Article Code

Complete Java source-code examples accompanying articles published on **Medium**. Each folder preserves the examples as shared with readers, including examples using external libraries.

> **Article links:** The original article URLs are not recorded in this repository. Add verified article titles and links below when available; no URLs have been guessed.

## Examples

- **Clustering — [`Clustering/`](Clustering/):** Java clustering examples and Weka K-means. The core examples use Java; `Weka/WekaKMeans.java` requires Weka.
- **Neural networks — [`NeuralNetwork/`](NeuralNetwork/):** A neural network implemented from scratch, XOR with DeepLearning4J, and handwritten-digit examples. The framework examples require DeepLearning4J/ND4J and possibly additional dependencies.
- **WebSockets — [`Websockets/`](Websockets/):** Java WebSocket client/server examples using Tyrus.

## Medium article links

The original article URLs are not recorded in this repository. Add verified titles and links when available:

- **Clustering:** *Published article link to be added.*
- **Neural networks:** *Published article link(s) to be added.*
- **WebSockets:** *Published article link to be added.*

A folder may contain code for more than one article. These are placeholders, not verified article-to-folder mappings.

## Running the examples

These are **article companion examples**, not a single Maven or Gradle application. There is currently no root build file or unified test command.

- **Java-only examples:** For example, compile and run `NeuralNetwork/BasicNeuralNetwork.java` from its directory with `javac BasicNeuralNetwork.java` and `java BasicNeuralNetwork`.
- **Weka:** `Clustering/Weka/WekaKMeans.java` imports Weka classes and reads `weather.arff`. The dataset is **not included** here; supply the appropriate dataset and Weka dependencies before running it.
- **DeepLearning4J:** The DL4J/ND4J examples require matching third-party library versions. No dependency manifest is included; consult the corresponding article for its original environment.
- **WebSockets:** The chat server imports `org.glassfish.tyrus.server.Server`, so a compatible Tyrus dependency is required. No project-wide dependency manifest is included.

Some examples use older library APIs and may need the versions used when their articles were written. To keep published examples recognizable, any modernization should be documented separately rather than silently changing the original code.
