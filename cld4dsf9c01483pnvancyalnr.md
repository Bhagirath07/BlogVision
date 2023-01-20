# #62 Machine Learning & Data Science Challenge 62

# What are autoencoders?

An **autoencoder** is a neural network that has three layers:

An input layer, a hidden layer which is also known as the encoding layer, and a decoding layer.

* This network is trained to reconstruct its inputs, which forces the hidden layer to try to learn good representations of the inputs.
    
* An autoencoder neural network is an unsupervised Machine-learning algorithm that applies backpropagation, setting the target values to be equal to the inputs.
    
* An autoencoder is trained to attempt to copy its input to its output.
    
* Internally, it has a hidden layer that describes a code used to represent the input.
    

### Autoencoder Components:

#### **Encoder:**

* In this, the model learns how to reduce the input dimensions and compress the input data into an encoded representation.
    

##### **Bottleneck**:

* In this, the layer contains the compressed representation of the input data. This is the lowest possible dimension of the input data.
    

#### **Decoder**:

* In this, the model learns how to reconstruct the data from the encoded represented to be as close to the original inputs as possible.
    

#### **Reconstruction Loss:**

* This method measures how well the decoder is performing and how close the output is related to the original input.
    

### Types of Autoencoders:

1. Denoising Auto Encoder (**DAE**)
    
2. Sparse Auto Encoder (**SAE**)
    
3. Variational Auto Encoder (**VAE**)
    
4. Contractive Auto Encoder (**CAE**)