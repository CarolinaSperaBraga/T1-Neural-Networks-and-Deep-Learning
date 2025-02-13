# SCC0270 - Neural Networks and Deep Learning
## Implementation of an Autoencoder

An autoencoder is a type of artificial neural network commonly used to learn efficient representations of data, typically for dimensionality reduction, data compression, or denoising (noise removal). It consists of two main parts: the encoder and the decoder.

The function of the encoder is to convert the input data into a compressed or encoded representation, usually in a space with lower dimensionality than the input space. This encoded representation captures the most important features of the input data. Then, the decoder receives the encoded representation of the data and attempts to reconstruct the original input from this representation. It performs the inverse process of the encoder, expanding the encoded representation back to the original dimensionality space.

During training, an autoencoder is fed with input data and optimized to minimize the difference between the original input and the reconstructed output. This is usually done using a loss function, such as the Mean Squared Error (MSE), which quantifies the difference between the input and the reconstructed output.

Autoencoders are a powerful tool in machine learning and are used in various applications, including pattern recognition, natural language processing, computer vision, and more.

The objective of this work is to implement an autoencoder using Python based on the concepts presented in class. The autoencoder should allow the user to define the architecture, that is, how many layers and how many neurons in each layer they wish to use.
