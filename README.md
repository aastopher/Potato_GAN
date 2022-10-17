# Potato Generating - DCGAN (Deep Convolutional Generative Adversarial Network)

The purpose of the Potato GAN is to introduce the concepts behind basic image generation using a simple implementation of Deep Convolutional Generative Adversarial Networks. We will detail a basic example of training DCGANs to reproduce images of a single class, exploring the concepts related to how GANs work in general.

### Running this notebook
* The notebook will check for the presence of the dataset, if the folder does not exist (it will not on first run) then it will download the dataset automatically.
* Given that the pickled models exist the models will automatically be loaded an usable on your current device pre-trained instead of needing to train a new model.
* The notebook will check for the pickled models, if either model does not exists it will begin to re-train on the current device.