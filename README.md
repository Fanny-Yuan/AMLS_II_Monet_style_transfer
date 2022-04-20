# AMLS2_CycleGAN

This code is for the final project of ELEL0135_AMLS2. This project works for a style transform task using CycleGAN, aiming to transform a photo to a painting with style of Monet. 

## Set up

### Environment

Google Colab GPU / Kaggle TPU v3-8

Tensorflow >=2.2

### External libraries

tensorflow, tensorflow_addons, matplotlib, IPython, tensorboard

## Run the code

### Train and generate

Run **CycleGAN_Colab.ipynb** to train your own model and generate images. Dataset can be downloaded directly by running this code. 
There are all steps of data preparing, model building, training and generation in this code.

A python version of train and test is also provided as **main.py**. 

### Evaluate

FID score is used to evaluate the quality of generated images objectively. Run **calculate_fid.ipynb** to evaluate your results. Change the path of images 
to your own dir before you run it.
