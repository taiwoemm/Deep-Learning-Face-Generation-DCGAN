# Deep-Learning-Face-Generation-DCGAN
In this project, a Deep Convolutional Generative Adversarial Network (DCGAN) is defined and trained on a dataset of faces. The goal is to get a generator network to generate *new* images of faces that look as realistic as possible!

The project will be broken down into a series of tasks from **loading in data to defining and training adversarial networks**. At the end of the notebook, you'll be able to visualize the results of your trained Generator to see how it performs; your generated samples should look like fairly realistic faces with small amounts of noise.

### Get the Data

The [CelebFaces Attributes Dataset (CelebA)](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) is used to train the adversarial networks.

This dataset is more complex than the number datasets (like MNIST or SVHN) and needs deeper networks and training the networks for a longer time to get good results. It is suggested that a GPU be utilized for training.

### Pre-processed Data

Each of the CelebA images has been cropped to remove parts of the image that don't include a face, then resized down to 64x64x3 NumPy images. Some sample data is shown below.

<img src='assets/processed_face_data.png' width=60% />

> If working locally, this data can be downloaded [by clicking here](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/November/5be7eb6f_processed-celeba-small/processed-celeba-small.zip)

This zip file needs to be extracted from the home directory of this notebook for further loading and processing. After extracting the data, the directory of data should be `processed_celeba_small/`
