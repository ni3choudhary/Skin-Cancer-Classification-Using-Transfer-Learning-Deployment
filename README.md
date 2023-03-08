# Skin-Cancer-Classification-Using-Transfer-Learning-Deployment

![Python 3.7.7](https://img.shields.io/badge/Python-3.7.7-brightgreen.svg)

### Problem statement:
A DL Classification project that helps in identifying Skin Cancer using Transfer Learning MobileNetV2 architecture. For Classification, We have used Basal Cell Carcinoma, Nevus and Melanoma classes.

### Dataset
You can find the dataset [here.](https://challenge.isic-archive.com/data/#2019)
- Download Directly from this <a href="https://isic-challenge-data.s3.amazonaws.com/2019/ISIC_2019_Training_Input.zip">link </a>
- Training Ground Truth <a href="https://isic-challenge-data.s3.amazonaws.com/2019/ISIC_2019_Training_GroundTruth.csv">link </a>

## setup
To create a project from scratch use following steps - -

- Clone the repository : https://github.com/ni3choudhary/Skin-Cancer-Classification-Using-Transfer-Learning-Deployment.git

- Inside the project root directory, Create Conda Environment using below command.
```console
$ conda create -n myenv python=3.7.7
``` 

Activate Conda Environment
```console
$ conda activate myenv
```
Install Libraries using below command or you can use conda commands also for installation if below command doesn't work for you.
```console
$ pip install -r requirements.txt
```
- Use Skin-Cancer-Data-Preparation.ipynb to separate the image for each category using the ground truth csv.

- Use Skin-Cancer-Data-Train-Test-Split.ipynb to make the train and test folder for each category. we have only used 100 test images for each category.

- Use Skin_Cancer_Classification_MobileNetV2Model.ipynb for model training and get the model saved file for future use.

• Please do ⭐ the repository, if it helped you in anyway.




