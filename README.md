# AlteredNet
manually curated dataset for detection of real and digitally manipulated imagery

## Introduction 
AlteredNet is a dataset of human photos that stores two versions of each image, original and digitally modified. AlteredNet is designed to solve binary classification tasks, making a distinction between classes:

- class 0: digitally modified images.
- class 1: real images.

Each real image from class 1 is modified based on a single criteria such as an increase in age, or happiness. The modification criteria can be used as a sub-class, dividing the samples into 10 classes, in addition to the main 2.

## Requirements
- pytorch
- torchvision
- CUDA
- matplotlib
- numpy
- pandas
- PIL
