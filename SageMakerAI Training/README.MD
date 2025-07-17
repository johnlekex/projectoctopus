Lab 3.4 - Student Notebook
Overview
This lab is a continuation of the guided labs in Module 3.

In this lab, you will split the data into three separate datasets:

Training Set - This will be used to train the model.
Validation Set - This will be used during training to validate the model.
Test Set - This will be held back and used to produce metrics after the model is trained. You will use this dataset in an upcoming lab.
With the split data, you will train a XGBoost model by using Amazon SageMaker.

Introduction to the business scenario
You work for a healthcare provider, and want to improve detection of abnormalities in orthopedic patients.

You are tasked with solving this problem by using machine learning (ML). You have access to a dataset that contains six biomechanical features and a target of normal or abnormal. You can use this dataset to train an ML model to predict if a patient will have an abnormality.

About this dataset
This biomedical dataset was built by Dr. Henrique da Mota during a medical residence period in the Group of Applied Research in Orthopaedics (GARO) of the Centre Médico-Chirurgical de Réadaptation des Massues, Lyon, France. The data has been organized in two different, but related, classification tasks.

The first task consists in classifying patients as belonging to one of three categories:

Normal (100 patients)
Disk Hernia (60 patients)
Spondylolisthesis (150 patients)
For the second task, the categories Disk Hernia and Spondylolisthesis were merged into a single category that is labeled as abnormal. Thus, the second task consists in classifying patients as belonging to one of two categories: Normal (100 patients) or Abnormal (210 patients).

Attribute information:
Each patient is represented in the dataset by six biomechanical attributes that are derived from the shape and orientation of the pelvis and lumbar spine (in this order):

Pelvic incidence
Pelvic tilt
Lumbar lordosis angle
Sacral slope
Pelvic radius
Grade of spondylolisthesis
The following convention is used for the class labels:

DH (Disk Hernia)
Spondylolisthesis (SL)
Normal (NO)
Abnormal (AB)
For more information about this dataset, see the Vertebral Column dataset webpage.

Dataset attributions
This dataset was obtained from: Dua, D. and Graff, C. (2019). UCI Machine Learning Repository (http://archive.ics.uci.edu/ml). Irvine, CA: University of California, School of Information and Computer Science.

Lab setup
Because this solution is split across several labs in the module, you must run the following cells so that you can load the data.







Congratulations!
You have completed this lab, and you can now end the lab by following the lab guide instructions.