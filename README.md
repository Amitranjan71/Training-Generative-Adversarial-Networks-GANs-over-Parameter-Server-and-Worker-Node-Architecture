# Training-Generative-Adversarial-Networks-GANs-over-Parameter-Server-and-Worker-Node-Architecture
The latest technological discovery in the field of artificial intelligence (AI) is the learning and widespread use of different Generative Adversarial Networks (GANs) applications. GANs have made progress in numerous applications like image editing, style transfer, scene generation, and so on. However, these types of generative models demand high computation because GANs are made out of two deep neural networks and in light of the fact that it trains on huge datasets. As with other AI models, GANs also face problems of insufficient data while training for some real-world situations. In numerous situations, available databases might be restricted and distributed over various worker nodes (i.e. end users) where the local datasets are intrinsically private and ultimately workers towards the end do not want to share them. In this paper, we addressed the issue of training GANs in a distributed way so that they can train over datasets that are distributed to various worker nodes. We have developed a training framework for GANs under the setting of the parameter server and worker node. Under this framework various workers can produce results similar to real data while keeping it completely in a distributed way and also keeping their information confidential. Test results obtained with the CIFAR-10 dataset indicate that our architecture can produce high-quality data samples that look similar to real data and can be used in various real-life applications.


# For documentation please run helpme.py
This model generate images and Discernment them on the basis of real images, gives surprising results, can apply arithmetic operations on generated images.


NOTE : You can tweak the parameter of training dataset, kernel, and filter functions (RELU can be replaced with LSTM for text generation Process)


# Installation
install pillow, numpy and mpi4py
install cuda (10.2) version of pytrorch and torchvision

# PreRequisite
Knowlege of Python (Basic[class, modules, function])
Pytorch, Neural Network
Activation Function.

To Train and Get Generated Images Run design.py
