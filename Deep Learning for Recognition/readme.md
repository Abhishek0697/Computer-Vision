# Image Compression with AutoEncoders


- Dataset: NIST36
- Loss Function: Pixel-wise squared error
- Training objective: The output of the network(decoder) should look similar to the input image. i.e. Mnimizing the pixel-wise squared error
- Network Architecture:<br>
Linear(1024 neurons) &rarr; ReLU &rarr; Linear(32 neurons) &rarr; ReLU &rarr; Linear(32 neurons) &rarr; ReLU &rarr; Linear(1024) &rarr; ReLU &rarr; Sigmoid

![](https://github.com/Abhishek0697/Computer-Vision/blob/main/Deep%20Learning%20for%20Recognition/data/Autoencoder%20outputs.png)
