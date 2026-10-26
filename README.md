# Code for Medium Articles

Java source code accompanying articles by [Javier Gonzalez on Medium](https://mscjaviergs.medium.com/). Browse an article below, then open its corresponding source code to explore the examples.

## Articles and source code

### Neural networks

- **[What is a Neural Network?](https://medium.com/analytics-vidhya/neural-networks-in-a-nutshell-with-java-b4a635a2c4af)** — Build a neural network in Java from scratch, including forward propagation and backpropagation. **Code:** [`BasicNeuralNetwork.java`](NeuralNetwork/BasicNeuralNetwork.java).
- **[DeepLearning4J: Getting Started](https://mscjaviergs.medium.com/neural-networks-getting-started-with-eclipse-deeplearning4j-897f3662832b)** — Train a neural network to learn XOR with DeepLearning4J. **Code:** [`ExampleXORWithDL4J.java`](NeuralNetwork/ExampleXORWithDL4J.java).
- **[DeepLearning4J: Simple Image Classification](https://mscjaviergs.medium.com/deeplearning4-for-image-classification-part-1-fc01cb2b1c62)** — Train an MNIST handwritten-digit classifier with DeepLearning4J. **Code:** [`digitsModel/`](NeuralNetwork/digitsModel/); see also the [`digitsApplication/`](NeuralNetwork/digitsApplication/) example.

### WebSockets

- **[WebSocket Programming with Java](https://medium.com/swlh/how-to-build-a-websocket-applications-using-java-486b3e394139)** — Build a Java WebSocket client and server using Eclipse Tyrus. **Code:** [`Websockets/`](Websockets/).

## Additional Java examples

- **[Clustering](Clustering/)** — Clustering examples in Java, including [Weka K-means](Clustering/Weka/WekaKMeans.java).

## Running the examples

The examples are independent Java source files, not a single application. Some require external libraries, and the versions used when the articles were published may differ from current releases.

- **Java from scratch:** In `NeuralNetwork/`, run `javac BasicNeuralNetwork.java` followed by `java BasicNeuralNetwork`.
- **DeepLearning4J examples:** Require compatible DeepLearning4J and ND4J libraries. Follow the linked articles for their original setup.
- **WebSocket example:** Requires a compatible Tyrus implementation.
- **Weka clustering:** Requires Weka and a `weather.arff` dataset, which is not included in this repository.

The source files are retained in their original locations so you can follow along with the articles.
