# Deep-Learning-Implementation
Implementation of various Deep Learning models in PyTorch targeting various problems.

**1. Hello World of Deep Learning:**\
Implemented a fully connected neural network to classify handwritten digits. Further performed network visualization to explore which node in different layers are firing to classify digits.

**2. Audio Denoising Using Fully Connected Network:**\
Implemented a fully connected neural network to learn the mask to denoise audio having chip eating noise.

**3. Audio Denoising Using 1D CNN:**\
Implemented a 1D convolutional neural network to learn the mask to denoise audio having chip eating noise.

**4. Audio Denoising Using 2D CNN:**\
Implemented a 2D convolutional neural network to learn mask to denoise audio having chip eating noise Suprisingly, 1D CNN outperforms 2D cnn. This can be reasoned by saying that audio data is kind of time series data and has only 2 dimentions, one is time and other is value at that time instance. It makes more sense to use 2D convs for data with 3 dimentions. For example Images

**5. Self-Supervised Learning Using Pretext Tasks:**\
Trained a CNN model on CIFAR-10 dataset using self-supervised learning by first learning visual representations and then using those representations to train the model using transfer learning. Compared the performance of the model with a baseline model.

**6. Network Compression Using SVD:**\
Reduced network parameters by usage of SVD on the parameters. Compared network performance with respect of number of parameters needed for the network to understand effect of network compression.

**7. Audio Denoising using RNN:**\
Implemented a Recurrent neural network to learn the mask to denoise 500 audio samples ifused with different types of noise.

**8. RNN as Generative Model:**\
Trained an RNN model to predict other half of an MNIST image (considered as sequence).

**9. Speaker Verification Using Siamese Network**\
Implemented a Siamese network to verify which audio clip belongs to which speaker.

**10. Variational-AutoEncoders:**\
Learned the gaussian distribution which can generate MNIST digits. Tried different combinations of parameters of the distribution to see effect on the generated digits.

**11. MNIST conditional GAN:**\
Trained a CNN model on CIFAR-10 dataset using self-supervised learning by first learning visual representations and then using those representations to train the model using transfer learning. Compared the performance of the model with a baseline model.

**12. Missing Value Imputation using conditional GAN:**\
Implemented a regularized conditional GAN to predict surrounding pixels given the center patch of an MNIST image. Implemented 3 type of architecture: Baseline, regularized GAN($\lambda$ = 0.1), regularized GAN($\lambda$ = 10) and compared their performance.
