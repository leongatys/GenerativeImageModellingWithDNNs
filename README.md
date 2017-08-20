# GenerativeImageModellingWithDNNs
Here I will share the code from the lectures of the course: Generative Image Modelling with Deep Neural Networks taught in the Summer Term 2017 at the Graduate School for Neural Information Processing, University of Tuebingen.
All code and implementations are such that they should comfortably run on a CPU.

## Prerequisites
- Install Docker on your machine (https://docs.docker.com/engine/installation/)
- Pull the docker container leongatys/pytorch-cpu with
`docker pull leongatys/pytorch-cpu`
- Start running a Notebook Server in the Docker Container by running: `docker run -v $HOME:/home -p 443:8888 -d leongatys/pytorch-cpu jupyter notebook --ip 0.0.0.0 --no-browser`
- Go to your browser and type 'localhost:443'  in the url bar. The browser should now show the Jupyter Notebook Server where you can navigate to this repository and open the Notebooks.

## Content
### Lecture 1
Brief introduction to natural images and example of classifying an image with a pre-trained CNN.
### Lecture 2
Discussion and implementation of [Deep Inside Convolutional Networks: Visualising Image Classification Models and Saliency Maps, Simonyan et al. 2013](https://arxiv.org/abs/1312.6034).  
Also implementation of the regularisation methods from [Understanding Neural Networks Through Deep Visualization, Yosinski et al. 2015 ](https://arxiv.org/pdf/1506.06579.pdf).
### Lecture 3
Discussion and implementation of [Understanding Deep Image Representations by Inverting Them, Mahendran et al. 2015](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Mahendran_Understanding_Deep_Image_2015_CVPR_paper.pdf).  
### Lecture 4
Discussion and implementation of [Intriguing properties of neural networks, Szegedy et al. 2014](https://arxiv.org/pdf/1312.6199.pdf).  
### Lecture 5
Discussion and implementation of [Texture Synthesis Using Convolutional Neural Networks, Gatys et al. 2015](http://papers.nips.cc/paper/5633-texture-synthesis-using-convolutional-neural-networks.pdf).  
### Lecture 6
Discussion and implementation of [Image Style Transfer Using Convolutional Neural Networks, Gatys et al. 2016](http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf).  
### Lecture 7
Discussion and implementation of [Generative Adversarial Nets, Goodfellow et al. 2014](http://papers.nips.cc/paper/5423-generative-adversarial-nets.pdf)
