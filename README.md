# Image-classification-With-Sagemaker
This project is based on how we can implement image classification deep learning models and deploy them using AWS Sagemaker.
This dataset is basically classifying 37 breeds of dogs images using deep learning algorithms . These models are being made to run on ml.p3.2xlarge EC2 instances which have 16GB GPU and then deployed in in ml.m4.xlarge instance where we can do our predictions on our trained model.
The ouput Artifact is stored in S3 bucket.
Technology Stack used:
Python programming language
AWS Sagemaker
Python libraries used :
os
tarfile
urllib
shutil
json
numpy 
boto3
sagemaker
tqdm
