# Potato Generating - DCGAN (Deep Convolutional Generative Adversarial Network)

The purpose of this project is to introduce the concepts behind basic image generation using a simple implementation of Deep Convolutional Generative Adversarial Networks. This project will detail a basic example, training DCGANs to reproduce images of a single class. Exploring the concepts related to how GANs work in general.

### Running this notebook
* The notebook will check for the presence of the dataset, if the folder does not exist (it will not on first run) then it will download the dataset automatically.
* Given that the pickled models exist, the models will automatically be loaded an usable on your current device pre-trained.
* The notebook will check for the pickled models, if either model does not exists it will begin to re-train on the current device. (i.e. just delete or remove the current model files to re-train)

### References

```
@misc{https://doi.org/10.48550/arxiv.1406.2661,
  doi = {10.48550/ARXIV.1406.2661},
  url = {https://arxiv.org/abs/1406.2661},
  author = {Goodfellow, Ian J. and Pouget-Abadie, Jean and Mirza, Mehdi and Xu, Bing and Warde-Farley, David and Ozair, Sherjil and Courville, Aaron and Bengio, Yoshua},
  keywords = {Machine Learning (stat.ML), Machine Learning (cs.LG), FOS: Computer and information sciences, FOS: Computer and information sciences},
  title = {Generative Adversarial Networks},
  publisher = {arXiv},
  year = {2014},
  copyright = {arXiv.org perpetual, non-exclusive license}
}
```
```
@misc{https://doi.org/10.48550/arxiv.1511.06434,
  doi = {10.48550/ARXIV.1511.06434},
  url = {https://arxiv.org/abs/1511.06434},
  author = {Radford, Alec and Metz, Luke and Chintala, Soumith},
  keywords = {Machine Learning (cs.LG), Computer Vision and Pattern Recognition (cs.CV), FOS: Computer and information sciences, FOS: Computer and information sciences},
  title = {Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks},
  publisher = {arXiv},
  year = {2015},
  copyright = {arXiv.org perpetual, non-exclusive license}
}
```
```
@misc{https://doi.org/10.48550/arxiv.1606.03498,
  doi = {10.48550/ARXIV.1606.03498},
  url = {https://arxiv.org/abs/1606.03498},
  author = {Salimans, Tim and Goodfellow, Ian and Zaremba, Wojciech and Cheung, Vicki and Radford, Alec and Chen, Xi},
  keywords = {Machine Learning (cs.LG), Computer Vision and Pattern Recognition (cs.CV), Neural and Evolutionary Computing (cs.NE), FOS: Computer and information sciences, FOS: Computer and information sciences}, 
  title = {Improved Techniques for Training GANs},
  publisher = {arXiv},
  year = {2016},
  copyright = {arXiv.org perpetual, non-exclusive license}
}
```
