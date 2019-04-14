## Project Overview

This repository hosts code used in fourth project on Generative Adversarial Networks (GAN) project in the Deep Learning Nanodegree. In addition to meeting the project specifications, I also added on a few things. 

The aim is to use generative adversarial networks to generate new images of faces.

## Project To Do List

### Rubrics
| Criteria                                           | Specifications                                                                                                                                                                                        | Finished |
|----------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------|
| Pre-processing Data | The function `get_dataloader` and `scale` is implemented |<ul><li>[ ] </li></ul>|
| Build the Adversarial Networks | Discriminator and Generator class is implemented correctly. Weight is initialized correctly. |<ul><li>[ ] </li></ul>|
| Optimization Strategy | `real_loss` and `fake_loss` functions implemented correctly and appropriate optimizers defined. |<ul><li>[ ] </li></ul>|
| Training and Results | Reasonable hyperparameters are selected for training and the model generates realistic faces. |<ul><li>[ ] </li></ul>|
| Prepare report    | Refer the [rubrics](https://review.udacity.com/#!/rubrics/2261/view)  |<ul><li>[ ] </li></ul>|


### Suggestions
- [ ] Create a deeper model and use it to generate larger (say 128x128) images of faces.
- [ ] Read existing literature to see if using padding and normalization techniques generates higher-resolution images.
- [ ] Implement a learning rate that evolves over time as they did in this [CycleGAN Github repo](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix).
- [ ] See if this model can be extend and use a CycleGAN to learn to swap different kinds of faces. For example, learn a mapping between faces that have and do not have eye/lip makeup, as they did in [this paper](https://gfx.cs.princeton.edu/pubs/Chang_2018_PAS/Chang-CVPR-2018.pdf).
