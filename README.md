# Deep-Learning-Implementation
Implementation of various Deep Learning models in PyTorch targeting various problems.

**1. Hello World of Deep Learning**
Implemented a fully connected neural network to classify handwritten digits. Further performed network visualization to explore which node in different layers are firing to classify digits.

**2. Audio Denoising using Fully connected network completed**
Implemented a fully connected neural network to learn the mask to denoise audio having chip eating noise.

**3. Audio Denoising using 1D CNN implemented**
Implemented a 1D convolutional neural network to learn the mask to denoise audio having chip eating noise.

**4. Audio Denoising using 2D CNN implemented**
Implemented a 2D convolutional neural network to learn mask to denoise audio having chip eating noise Suprisingly, 1D CNN outperforms 2D cnn. This can be reasoned by saying that audio data is kind of time series data and has only 2 dimentions, one is time and other is value at that time instance. It makes more sense to use 2D convs for data with 3 dimentions. For example Images
