# DL-Face-Generation-GAN

## Introduction

In this project, you'll use generative adversarial networks to generate new images of faces. The goal is to get a generator network
to generate new images of faces that look as realistic as possible!

The project will be broken down into a series of tasks from loading in data to defining and training adversarial networks. 
At the end of the notebook, you'll be able to visualize the results of your trained Generator to see how it performs; 
your generated samples should look like fairly realistic faces with small amounts of noise.

## Get the Data

You'll be using the [CelebFaces Attributes Dataset (CelebA)](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) to train your adversarial
networks.

## Project dependencies

### Installation

Download Anaconda and install Anaconda on your machine.

### Create and Activate the Environment

Create a environment using following command

```
conda create --name deep-learning
```
Then activate the environment using following command

```
activate deep-learning
```

### Git and version control

These instructions also assume you have git installed for working with Github from a terminal window, but if you do not, you can download 
that first with the command:

```
conda install git
```

Now, you can create a local version of the project

Clone the repository, and navigate to the downloaded folder. This may take a minute or two to clone due to the included image data.

```
git clone https://github.com/ChitraChaudhari/DL-Face-Generation-GAN.git
cd TV-Script-Generation
```
Install PyTorch and torchvision; this should install the latest version of PyTorch.

Linux or Mac:
```
conda install pytorch torchvision -c pytorch 
```
Windows:
```
conda install pytorch -c pytorch
pip install torchvision
```
Install a few required pip packages, which are specified in the requirements text file (including OpenCV).
```
pip install -r requirements.txt
```
That's it!, Now run the project using following command, check you default browser and open dlnd_face_generation.ipynb file
```
jupyter notebook
```
