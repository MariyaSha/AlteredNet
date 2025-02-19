# AlteredNet
manually curated dataset for detection of real and digitally manipulated imagery

## Introduction 
AlteredNet is a dataset of human photos that stores two versions of each image, original and digitally modified. AlteredNet is designed to solve binary classification tasks, making a distinction between classes:

- class 0: digitally modified images.
- class 1: real images.

Each real image from class 1 is modified based on a single criteria such as an increase in age, or happiness. The modification criteria can be used as a sub-class, dividing the samples into 10 classes, in addition to the main 2.

<img src="https://github.com/user-attachments/assets/b6742f8e-3366-4790-a8e2-919ce2b6ca64" width="600px">
<br>
<img src="https://github.com/user-attachments/assets/8bad8870-e49f-490f-971f-d88cf6de12b2" width="600px">

## Requirements
- pytorch
- torchvision
- CUDA
- matplotlib
- numpy
- pandas
- PIL
