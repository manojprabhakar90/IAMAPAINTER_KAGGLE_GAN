**Introduction
**
This is part of MSDS program at University of Colorado Boulder. This is part of the Introduction to Deep Learning course. 

We recognize the works of artists through their unique style, such as color choices or brush strokes. The “je ne sais quoi” of artists like Claude Monet can now be imitated with algorithms thanks to generative adversarial networks (GANs). In this getting started competition, you will bring that style to your photos or recreate the style from scratch!

Computer vision has advanced tremendously in recent years and GANs are now capable of mimicking objects in a very convincing way. But creating museum-worthy masterpieces is thought of to be, well, more art than science. So can (data) science, in the form of GANs, trick classifiers into believing you’ve created a true Monet? That’s the challenge you’ll take on!

The Challenge: A GAN consists of at least two neural networks: a generator model and a discriminator model. The generator is a neural network that creates the images. For our competition, you should generate images in the style of Monet. This generator is trained using a discriminator.

The two models will work against each other, with the generator trying to trick the discriminator, and the discriminator trying to accurately classify the real vs. generated images.

Our task is to build a GAN that generates 7,000 to 10,000 Monet-style images.
**
Data:**

We are provided with monet paintings both in JPG and TFRecords format as our training data.

There are 300 monet images and 7038 JPG images

The image size is (256,256, 3)

The model uses a DCGAN architecture and can leverage multiple GPU's if its available. The noise dimension that has been used is 200. It can be further tweaked.

The number of epochs is 1000. Can be more. 

Competition link: https://www.kaggle.com/competitions/gan-getting-started
