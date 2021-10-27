# MIMIC-III (BMI-500)
BMI 500 Lab 7 using the MIMIC III Dataset 

SQl : Please visit the following link for step by step on how to run SQL using Bigquery on google cloud 
https://mimic.mit.edu/docs/iii/tutorials/intro-to-mimic-iii-bq/

SQL files are AKI_Stages.sql and Before_AKI.sql. AKI_Stages.sql checks to see if the patient has AKI based on the KDIGO definition while Before_AKI.sql checks to see if the patient has AKI based on the KDIGO definition and returns stages of zero. Both require 294.4 MB. 

Clustering.ipynb is a Jupyter notebook for Kmeans clustering . IT requires the following libraaries pandas,numpy and sklearn.

The data is too large to be updates , thus one can refer to the clustering notebook for snippets of the data.
