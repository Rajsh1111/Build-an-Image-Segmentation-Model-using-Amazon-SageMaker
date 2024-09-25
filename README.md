# Build-an-Image-Segmentation-Model-using-Amazon-SageMaker
Project Description
Overview:
Amazon SageMaker is a machine learning service where data scientists can train and deploy their machine learning models. It provides an integrated Jupyter authoring notebook instance to access the data sources for exploration and analysis efficiently. To make the work of data scientists easy, it provides easy deployment of the model in the hosted environment so that they don’t have to rely upon software engineers for it. SageMaker enables jobs to preprocess, and post-process the data. The user can also do feature engineering, and evaluate their models. 
 
In this project, we will build an image segmentation model in Tensorflow on Amazon SageMaker using the UNet model architecture. The project will also be deployed on the SageMaker. 

Aim of Project:
•	To understand image segmentation
•	To train and deploy the image segmentation model on Amazon SageMaker

Tech Stack used:
•	Language: Python
•	Libraries: tensorflow, pandas, numpy, sklearn, patchify, matplotlib, segmentation_models, boto3

Data Description:
The dataset contains images of apples that are rotten. The images will be used to train the model. The rotten part of the apples is annotated. 

Approach:
•	Data Loading
•	Data Preprocessing
o	Image Patching
•	Model Building and Training
o	Segmentation model in tensorflow
•	Model Deployment on Amazon SageMaker
