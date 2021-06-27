# Computer Vision Repository


Computer vision is the field of computer science that focuses on replicating parts of the complexity of the human vision system and enabling computers to identify and process objects in images and videos in the same way that humans do

You can look at my work on Computer Vision in this repository.

In this repository, you will find my works in ***src*** folder:

* ### [ANN](https://github.com/ugurcankok/Computer_Vision/tree/master/src/ANN)

 <img src="https://ars.els-cdn.com/content/image/1-s2.0-S0269749119312631-fx1.jpg" width="400" height="200">

 An artificial neural network (ANN) is the piece of a computing system designed to simulate the way the human brain analyzes and processes information. It is the foundation of artificial intelligence (AI) and solves problems that would prove impossible or difficult by human or statistical standards. ANNs have self-learning capabilities that enable them to produce better results as more data becomes available. 
 
 Artificial neural networks are built like the human brain, with neuron nodes interconnected like a web. The human brain has hundreds of billions of cells called neurons. Each neuron is made up of a cell body that is responsible for processing information by carrying information towards (inputs) and away (outputs) from the brain.
 
 An ANN has hundreds or thousands of artificial neurons called processing units, which are interconnected by nodes. These processing units are made up of input and output units. The input units receive various forms and structures of information based on an internal weighting system, and the neural network attempts to learn about the information presented to produce one output report. Just like humans need rules and guidelines to come up with a result or output, ANNs also use a set of learning rules called backpropagation, an abbreviation for backward propagation of error, to perfect their output results.

* ### [Autoencoder](https://github.com/ugurcankok/Computer_Vision/tree/master/src/Autoencoder)

 <img src="https://miro.medium.com/max/3148/1*44eDEuZBEsmG_TCAKRI3Kw@2x.png" width="400" height="200">
 
 Autoencoders are an unsupervised learning technique in which we leverage neural networks for the task of representation learning. Autoencoders are a specific type of feedforward neural networks where the input is the same as the output. They compress the input into a lower-dimensional code and then reconstruct the output from this representation. The code is a compact “summary” or “compression” of the input, also called the latent-space representation.
 
 An autoencoder consists of 3 components: encoder, code and decoder. The encoder compresses the input and produces the code, the decoder then reconstructs the input only using this code.

* ### [CNN](https://github.com/ugurcankok/Computer_Vision/tree/master/src/CNN)

 <img src="https://miro.medium.com/max/1644/1*uAeANQIOQPqWZnnuH-VEyw.jpeg" width="400" height="200">
 
 In deep learning, a convolutional neural network (CNN, or ConvNet) is a class of deep neural network, most commonly applied to analyze visual imagery. CNNs are regularized versions of multilayer perceptrons. Multilayer perceptrons usually mean fully connected networks, that is, each neuron in one layer is connected to all neurons in the next layer. The "full connectivity" of these networks make them prone to overfitting data.
 
 In the context of a convolutional neural network, a convolution is a linear operation that involves the multiplication of a set of weights with the input, much like a traditional neural network. Given that the technique was designed for two-dimensional input, the multiplication is performed between an array of input data and a two-dimensional array of weights, called a filter or a kernel.

* ### [GANs](https://github.com/ugurcankok/Computer_Vision/tree/master/src/GANs)

 <img src="https://www.researchgate.net/publication/340458845/figure/fig1/AS:879437700669440@1586685695381/The-architecture-of-vanilla-GANs.ppm" width="400" height="200">
 
 Generative modeling is an unsupervised learning task in machine learning that involves automatically discovering and learning the regularities or patterns in input data in such a way that the model can be used to generate or output new examples that plausibly could have been drawn from the original dataset.
 
 GANs are a clever way of training a generative model by framing the problem as a supervised learning problem with two sub-models: the generator model that we train to generate new examples, and the discriminator model that tries to classify examples as either real (from the domain) or fake (generated). The two models are trained together in a zero-sum game, adversarial, until the discriminator model is fooled about half the time, meaning the generator model is generating plausible examples.

* ### [ResNet](https://github.com/ugurcankok/Computer_Vision/tree/master/src/ResNet)

 <img src="https://developer.ridgerun.com/wiki/images/f/f5/Resnet_architecture.png" width="400" height="200">
 
 In order to solve the problem of the vanishing/exploding gradient, this architecture introduced the concept called Residual Network. In this network we use a technique called skip connections . The skip connection skips training from a few layers and connects directly to the output. The approach behind this network is instead of layers learn the underlying mapping, we allow network fit the residual mapping. So, instead of say H(x), initial mapping, let the network fit, F(x) := H(x) – x which gives H(x) := F(x) + x.
 
 The advantage of adding this type of skip connection is because if any layer hurt the performance of architecture then it will be skipped by regularization. So, this results in training very deep neural network without the problems caused by vanishing/exploding gradient
