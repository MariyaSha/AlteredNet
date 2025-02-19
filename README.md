# AlteredNet
manually curated dataset for detection of real and digitally manipulated imagery

## Introduction 
AlteredNet is a dataset of human photos that stores two versions of each image, original and digitally modified. AlteredNet is designed to solve binary classification tasks, making a distinction between classes:

- class 0: digitally modified images.
- class 1: real images.

<img src="https://github.com/user-attachments/assets/4f75b0df-4a33-469b-9872-a97b2080c334" width="600px">

## Modification Criteria
Each real image from class 1 is modified based on a single criteria such as an increase in age, or happiness. The modification criteria can be used as a sub-class, dividing the samples into 10 classes, in addition to the main 2.
<br>
<br>
<img src="https://github.com/user-attachments/assets/35bb210a-79d1-4a66-9934-968063f1d303" width="600px">

## Repository Content

### Detailed Report
You can find the full project report, as submitted to UoL, at the root directory as **AlteredNet Report.pdf**.
<br>
The report presents the curation workflow, methodology, literature review, planning, design, implemintation, user testing, results, etc.

### Classification
You can find the full code, used to implement, train and test assorted state of the art neural netowrks on AlteredNet samples, also at the root directory as **AlteredNet_Classification.ipynb**

### Data
You can find the full AlteredNet dataset, including the test, train and validation sets along with labels and modification criterias for each image, in the **data** directory of this repository.

### User Testing
You can find the user testing results and analysis methods in the **user_testing** directory of this repository.

## Requirements
- pytorch
- torchvision
- CUDA
- matplotlib
- numpy
- pandas
- PIL
