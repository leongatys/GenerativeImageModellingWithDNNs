# GenerativeImageModellingWithDNNs
Here I will share the code from the lectures of the course: Generative Image Modelling with Deep Neural Networks taught in the Summer Term 2017 at the Graduate School for Neural Information Processing, University of Tuebingen.
## Prerequisites
- Install Docker on your machine (https://docs.docker.com/engine/installation/)
- Pull the docker container leongatys/pytorch-cpu with
`docker pull leongatys/pytorch-cpu`
- Start running a Notebook Server in the Docker Container by running: `docker run -v $HOME:/home -p 443:8888 -d leongatys/pytorch-cpu jupyter notebook --ip 0.0.0.0 --no-browser`
- Go to your browser and type 'localhost:443'  in the url bar. The browser should now show the Jupyter Notebook Server where you can navigate to this repository and open the Notebooks.

## Content
### Lecture 1
Brief introduction to natural images and example of classifying an image with a pre-trained CNN.
