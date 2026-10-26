# Medium Article Code

Complete Java source-code examples accompanying articles published on **Medium**. Each folder preserves the examples as shared with readers, including examples using external libraries.

> **Article links:** The original article URLs are not recorded in this repository. Add verified article titles and links below when available; no URLs have been guessed.

## Examples

| Topic | Source | What it demonstrates | Dependencies |
| --- | --- | --- | --- |
| Clustering | [`Clustering/`](Clustering/) | Java clustering examples and a Weka K-means example | Core examples: Java; `Weka/WekaKMeans.java`: Weka |
| Neural networks | [`NeuralNetwork/`](NeuralNetwork/) | A neural network from scratch, XOR with DeepLearning4J, and handwritten-digit examples | Core `BasicNeuralNetwork.java`: Java; other examples: DeepLearning4J/ND4J and potentially additional dependencies |
| WebSockets | [`Websockets/`](Websockets/) | Java WebSocket client/server | Tyrus WebSocket implementation |

## Finding the article for an example

| Source | Medium article |
| --- | --- |
| `Clustering/` | *Link to published article to be added* |
| `NeuralNetwork/` | *Link(s) to published article(s) to be added* |
| `Websockets/` | *Link to published article to be added* |

The folders are organized by code topic, not necessarily one folder per article. The mapping above is a placeholder until the exact published articles can be verified.

## Running the examples

These are **article companion examples**, not a single Maven or Gradle application. There is currently no root build file or unified test command.

- **Java-only examples:** For example, compile and run `NeuralNetwork/BasicNeuralNetwork.java` from its directory with `javac BasicNeuralNetwork.java` and `java BasicNeuralNetwork`.
- **Weka:** `Clustering/Weka/WekaKMeans.java` imports Weka classes and reads `weather.arff`. The dataset is **not included** here; supply the appropriate dataset and Weka dependencies before running it.
- **DeepLearning4J:** The DL4J/ND4J examples require matching third-party library versions. No dependency manifest is included; consult the corresponding article for its original environment.
- **WebSockets:** The chat server imports `org.glassfish.tyrus.server.Server`, so a compatible Tyrus dependency is required. No project-wide dependency manifest is included.

Some examples use older library APIs and may need the versions used when their articles were written. To keep published examples recognizable, any modernization should be documented separately rather than silently changing the original code.

## Repository policy

- Preserve original example filenames, directory paths, and behavior so readers can follow the articles.
- Add verified article links and dependency/version notes as they become available.
- Keep generated `.class` files, build outputs, and local IDE settings out of version control.

This repository is a **source-code archive for published articles**, not a maintained production application.
