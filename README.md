<!-- Add banner here -->
![Banner](https://unsplash.com/photos/3KGF9R_0oHs)
https://unsplash.com/photos/bY5OUwKx3XU

# Brain Tumor Classification through different Architectures.
<!-- Technology stack badges-->
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Sublime Text](https://img.shields.io/badge/sublime_text-%23575757.svg?style=for-the-badge&logo=sublime-text&logoColor=important)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)



<!-- Describe your project in brief -->

Objective: This project was for learning purpose, both to understand the difference in various types of tumors. As well as how Deep Learning Architectures are built, various underlying concepts as well as concepts invovled. 

Data : The original data was taken from ![Kaggle](https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection)  - Credits to ![Navoneel Chakrabarty] https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection
More details of dataset is in ![DataSheet](https://github.com/ameya-9/BrainTumorClassification-MRIs-/blob/main/datasets/DataSheet)



# Lets get Started

![Random GIF](https://media.giphy.com/media/ZVik7pBtu9dNS/giphy.gif)


# Table of contents



- [Project Title](#Brain Tumor Classification)
- [Table of contents](#table-of-contents)
- [Theory](#theory)
- [Details of Architecutre](#architecture)

# Theory
![](https://unsplash.com/photos/BDKid0yJcAk)

[(Back to top)](#theory)
A brain tumor is a mass or growth of abnormal cells in your brain.
Quick Facts about Brain Tumors : 
An estimated 700,000 Americans are living with a primary brain tumor.
Approximately 70% of all brain tumors are benign.
Approximately 30% of all brain tumors are malignant.


Different kinds of Brain Tumors (part of dataset): 
## Gliomas: 
These tumors begin in the brain or spinal cord and include astrocytomas, ependymomas, glioblastomas, oligoastrocytomas and oligodendrogliomas.
## Meningiomas. 
A meningioma is a tumor that arises from the membranes that surround your brain and spinal cord (meninges). Most meningiomas are noncancerous.

## Pituitary adenomas:
These are tumors that develop in the pituitary gland at the base of the brain. These tumors can affect the pituitary hormones with effects throughout the body.



# Architectures 
[(Back to top)](#architecture)

There were three Neural Network Architecutre that I modeled and trained over the train test. 
1. Dense_Model ( Without drop outs)
2. Dense_Model_with_dropouts ( with drop outs)
3. Vgg16 ( Model is provided in Tensorflow; off the shelf implementation)  
 
 


DenseModel: 
<!-- ![image](https://user-images.githubusercontent.com/19268537/145747090-9bcbc166-9ba9-48c3-b14a-69ea09637dc6.png) -->
<img src="https://user-images.githubusercontent.com/19268537/145747090-9bcbc166-9ba9-48c3-b14a-69ea09637dc6.png" width="300" height="800" />
Dense Model with Dropouts : 
<!-- ![image](https://user-images.githubusercontent.com/19268537/145747189-e09ae4b6-76d0-4c3f-a554-9803fc692210.png) -->
<img src="https://user-images.githubusercontent.com/19268537/145747189-e09ae4b6-76d0-4c3f-a554-9803fc692210.png" width="300" height="800" />


Vgg16 Architecture : 
<!-- ![vgg16](https://user-images.githubusercontent.com/19268537/145748712-977f72c7-273a-4c43-aa48-d21f22f541ef.jpeg) -->
<img src="![vgg16](https://user-images.githubusercontent.com/19268537/145748958-ac916022-3fae-43f6-86cc-fe7c4267650d.jpeg)" width="300" height="900" />

<!-- Accuracy and Loss Graphs on Different Epochs: 
![15Epochs](https://user-images.githubusercontent.com/19268537/145749000-1b00d077-d122-4460-ab37-88b953a25c19.png)
![50Epochs](https://user-images.githubusercontent.com/19268537/145749010-c6bce58b-0c2d-4458-9891-807f4b9cf64b.png)
![dense_model_with_dropoutAccuracy 50](https://user-images.githubusercontent.com/19268537/145749015-6a762345-571e-4910-94d3-9c374fae1712.png)
![dense_model_with_dropoutLoss50](https://user-images.githubusercontent.com/19268537/145749024-2bdfbed7-df5e-4bf5-a3eb-1399b782c191.png)
![dense_model50](https://user-images.githubusercontent.com/19268537/145749031-5760c33f-1b41-4e23-9b34-382df6db7056.png)
![model_vgg16loss50](https://user-images.githubusercontent.com/19268537/145749040-be4c9848-5cb2-44ba-9194-976a18b3a22f.png)
![modelvgg16Accuracy50](https://user-images.githubusercontent.com/19268537/145749042-005b2966-0057-4295-8b00-e40ff79ccdf6.png)
 -->


# References
[(Back to top)](#table-of-contents)

Brain Tumor Information : 
![Mayo Clinic](https://www.mayoclinic.org/diseases-conditions/brain-tumor/symptoms-causes/syc-20350084)
![Brain Tumor Statistics](https://braintumor.org/brain-tumor-information/brain-tumor-facts/?gclid=Cj0KCQiA2NaNBhDvARIsAEw55hjOm-s0eZX6l-hPK4RSXi3OrNk0qVlqpsTWqnHxBPLTCnsi3LTIYVoaAhP9EALw_wcB)
