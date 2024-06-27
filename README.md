# Running the code
> Note: [Pdf](Project2.pdf) file is well formatted and easy to read.

## Requirements
- **Jupyter Notebook Support**
- Run `pip install -r requirements.txt` to install all the dependencies in your environment.

## Running the code
- Run `jupyter notebook` in your terminal to open the notebook in your browser.
- Open the `Project2.ipynb` file and run the cells in the notebook.

## Simply want to see the results?
- Open the `Project2.pdf` file to see the results of the notebook.

> The model will be saved in the `model` folder in the format of date and time of training.

## Author

|Name                       | Roll Number   |
|---                        |---            |
|Yelisetty Karthikeya S M   | 21CS30060     |

Github: [lurkingryuu](https://github.com/lurkingryuu)

---
# Project-II

## Dataset
The folder [Dataset2](./Dataset2/) contains 2 folders, the [FNA](./Dataset2/FNA/) named folder contains 2 more folders ( [benign](./Dataset2/FNA/benign/) folder contains image datas for 1074 benign cases and [malignant](./Dataset2/FNA/malignant/) folder contains image datas for 650 malignant cases).

## Overview: 
1. Preprocessing of given labelled image datas (inside ‘FNA’ files).

2. Train and validate your model (CNN) with those preprocessed images.

3. Estimate and plot training and validation loss and accuracy function.

4. Fit the unlabelled images from file ‘test’ to your model and predict malignant or benign.

## Objective: 
1. The folder “test” inside folder “Dataset2” contains unlabelled 14 images. Predict benign or malignant for those cases. [Use a CNN (Convolutional Neural Network) OR any other deep neural network for training purpose].

2. Evaluate the model accuracy and loss function.