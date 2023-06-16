# PlantCare-Machine-Learning

# What machine learning's team do?

We search for datasets and build machine model to detect disease for tomato's leaf disease and apple's leaf disease. We build 2 model for this app. For tomato's leaf disease, we can classify 11 classes : 10 for diseases and 1 for healthy. For apple's disease, we can classify 7 classes : 6 for diseases and 1 for healthy.  

## 1. Search datasets for the disease
We search and get the datasets for our model from different resource. Here the sources from our datasets that we use :  
Tomato : https://www.kaggle.com/datasets/cookiefinder/tomato-disease-multiple-sources  
Apple : https://github.com/JasonYangCode/AppleLeaf9  

## 2. Get information for every disease in datasets  
We do research for the diseases, apple's leaf disease and tomato's leaf disease. We get these informations from various source, such as :  
https://plantvillage.psu.edu/topics/apple/infos  
https://plantvillage.psu.edu/topics/tomato/infos  

## 3. Preparation data  
We do clean and delete several unnecessary images in the datasets, especially from the apple's dataset. Here is final dataset for apple that finally we use for the model :  
https://drive.google.com/uc?id=1Uj3O9QK758M_NkMxPEgdYPmDWzzjDwyF  

## 4. Create model and train data  
For the tomato's model, we use transfer learning DenseNet. Here is the model :  
https://github.com/PlantCareTeam/PlantCare-Machine-Learning/blob/main/Model%20Tomato.ipynb  
For the apple's model, we don't use transfer learning. Here is the model :  
https://github.com/PlantCareTeam/PlantCare-Machine-Learning/blob/main/Model%20Apple.ipynb  
We do train for the model using datasets that we've mentioned before.  

## 5. Evaluate the model  
From the training that we've conducted, we obtained the following results :  
For the tomato's model, we got 97,7% accuracy and 0,06% loss.  
[insert gambar]  
For the apple's model, we got 92,9% accuracy and 0,21% loss.  
[insert gambar]  

