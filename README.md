# ♻️ Capstone Project Bangkit 2024 - EcoPlan ♻️

<p align="center">
  <img src="https://github.com/user-attachments/assets/71c1035c-5b8f-442b-a3fa-4a853f922a85" alt="Logo EcoPlan" width="300">
  <h1 align="center">ECOPLAN</h1>
</p>

<div align="center">
  This is a project to fulfill the <a href="https://contributors.bangkit.academy/">Bangkit Academy led by Google, Tokopedia, Gojek, & Traveloka</a> Program. <br> <br>
  <a href="https://docs.google.com/document/d/1dSUFNTHsdmhguiNQ3LHJkHQ6VtUIQoeal_LjvRUg33w/edit?tab=t.0">Project Brief</a> · <a href="https://docs.google.com/document/d/1l2-pESHdo2yg_AdGSLgEvHAy8FBYYTIw7NIhWUQ9DyI/edit?tab=t.0">EcoPlan Website Link</a> · <a href="https://youtu.be/kBf8GK6YnS4">Video Presentation</a> · <a href="https://www.canva.com/design/DAGZFe4bhb0/z_DYhoM3z3arhYwt5BeNMA/edit?utm_content=DAGZFe4bhb0&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton">Presentation Slide</a> <br>
  &copy C242-PR602 Bangkit Capstone Team 2024
</div>
<br>

## Table of Contents
- [Group Members](#-group-members)
- [About EcoPlan](#%EF%B8%8F-about-ecoplan)
- [Project Documentation](#-project-documentation)
    - [Web Development](#web-development)
    - [Machine Learning](#machine-learning)
    - [Cloud Computing](#cloud-computing)
- [Demo Website](#-demo-website)

## <a id="-group-members" style="color: inherit; text-decoration: none;">👩‍💻👨‍💻 Group Members</a>
### Group ID : C242-PR602
| Student ID     | Name                      | Learning Path   | Linkedin Profile |
|:--------------:|:-------------------------:|:---------------:|:----------------:|
| C227B4KY0420   | Alvian Hidayat            | Cloud Computing |[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alvian-hidayat-b54479221/)|
| C239B4KY1508   | Filbert Valentino Hartono | Cloud Computing |[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/filbert-hartono-54487a24a/)|
| C006B4KY2537   | Moestain Ramli Putra      | Cloud Computing |[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/moestain-ramli-putra-007477220/)|
| M297B4KX4142   | Shinta Nursobah Chairani  | Machine Learning|[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shinta-nursobah-chairani/)|
| M225B4KY4550   | Yossi Rifky Shabara       | Machine Learning|[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/baara/)|
<br>

## <a id="-about-ecoplan" style="color: inherit; text-decoration: none;">🖥️ About EcoPlan</a> 
According to KLHK, Indonesia produces 68.5 million tons of waste each year, with only 7.5% being recycled.   The low awareness of waste separation inspired us to develop solutions to improve waste management in the surrounding neighborhood. <br>
According to Sustainable Waste Indonesia (SWI), 24% of waste in Indonesia is poorly managed, ending up in rivers or illegal dumping sites, which contributes to severe environmental pollution. This highlights the urgent need for practical waste management solutions in local communities. <br>
EcoPlan, a web-based application, aims to improve waste management and sustainability practices, especially in the surrounding environment. It provides an easy-to-use solution for young people and communities to identify and separate waste, encouraging environmentally conscious behavior. <br>
<br>

## 📖 Project Documentation
### Web Development
### Machine Learning
[![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1DCt7lW71whp4Mry11fjQXb7e2Rdodp-e?usp=sharing)
#### Tools And Library
![Screenshot 2024-12-12 025758](https://github.com/user-attachments/assets/d116018d-a617-441b-b2f2-da639612e86c)

#### Dataset Kaggle 
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/datasets/mostafaabla/garbage-classification)
<br>
We've split the dataset into a training, a validation, and a testing set following an 80:10:10 ratio to ensure unbiased model evaluation.
#### Model Information
Model: "sequential_2"
|Layer (type) | Output Shape | Param # |
|:-----------:|:------------:|:-------:|
|mobilenetv2_1.00_224 (Functional)|(None, 7, 1280)|2,257,984|
|global_average_pooling2d (GlobalAveragePooling2D)|(None, 1280)|0|
|batch_normalization_6 (BatchNormalization)|(None, 1280)|5,120|
|dense_4 (Dense)|(None, 128)|163,968|
|dropout_2 (Dropout)|(None, 128)|0|
|dense_5 (Dense)|(None, 12)|1,548|


Total_params: 2,428,620 (9.26 MB) <br>
Trainable_params: 580,876 (2.22 MB) <br>
Non-trainable params: 1,847,744 (7.05 MB) <br>

![Screenshot 2024-12-12 024158](https://github.com/user-attachments/assets/2048e70e-35fa-43f9-b951-cfb945cb59dd)

#### Evaluation
```
Test Loss     : 0.2228
Test Accuracy : 0.9269
```

#### Save Model
[cnn_model_garbage_12_classes.h5](https://drive.google.com/file/d/15kahaeOdI9y8aOUsf1bsXUUt8Q9Zjfhm/view?usp=sharing)
### Cloud Computing

## 📱 Demo Website
### Demo with camera in Phone
### Demo with upload image in Phone
### Demo with camera in Desktop
### Demo with upload image in Desktop
