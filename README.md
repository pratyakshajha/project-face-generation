## Project Overview

This repository hosts code used in fourth project on Generative Adversarial Networks (GAN) project in the Deep Learning Nanodegree. In addition to meeting the project specifications, I also added on a few things. 

The aim is to use generative adversarial networks to generate new images of faces.

## Getting started
Open the `face_generation.ipynb` on a GPU enabled Python notebook environment, or Google colab (a link is directly on top in the notebook file). The notebook consists of further technical details. Run the notebook to generate your own unique and random face images.

### Further improvements
- [ ] Create a deeper model and use it to generate larger (say 128x128) images of faces.
- [ ] Read existing literature to see if using padding and normalization techniques generates higher-resolution images.
- [ ] Implement a learning rate that evolves over time as they did in this [CycleGAN Github repo](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix).
- [ ] See if this model can be extend and use a CycleGAN to learn to swap different kinds of faces. For example, learn a mapping between faces that have and do not have eye/lip makeup, as they did in [this paper](https://gfx.cs.princeton.edu/pubs/Chang_2018_PAS/Chang-CVPR-2018.pdf).
