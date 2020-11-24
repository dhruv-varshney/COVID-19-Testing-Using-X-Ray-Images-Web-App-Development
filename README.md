## PROBLEM STATEMENT :
Existing process of the getting information of covid-19 x-ray images and Pneumonia normal images is
extracted from online available resources. World Health Organization has declared Covid-19 as a
pandemic. There are a number of test kits available but are either expensive or take time to detect the
virus. Deep Learning is State-of-the-art machine learning algorithm and has shown massive
development in detecting Covid-19 with the help of chest X-rays.
In this blog, we will learn to detect Covid-19 with help Chest X-rays using CNN architechture.Thus
providing this purpose with necessary functionalities.

## SOFTWARE REQUIREMENTS SPECIFICATIONS :
Software requirements : Minimum software requirements are:
1)Tool : Anaconda, CNN Architechture
2)Operating System : Windows XP/7,8,10
3)Scripting Language : Python, Flasks
4)X-Ray Images : COVID-19, Pneumonia normal

## System Design
Our proposed deep learning-based COVID-19 detection comprises several phases, as illustrated in Figure. The phases are summarised in the following five steps:
Step 1: Collect the chest X-ray images for the dataset from COVID-19 patients and healthy persons.
Step 2: Generate Chest X-ray images using data augmentation.
Step 3: Represent the images in a feature space and apply deep learning.
Step 4: Split the dataset into two sets: a training set and a validation set.
Step 5: Evaluate the performance of the detector on the validation dataset.

## DATASET : 
COVID-19 images used in training are from https://github.com/ieee8023/covid-chestxray-dataset

## Normal Images
Dataset: Chest X-Ray Images (Pneumonia), https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia
It has two types of X-Ray images Normal and Pneumonia but only normal X-Rays have been used from this dataset so that Model learns to identify Covid-19 cases.

## Contributers:

1)B. Praveen Nayak   praveennayakbalaji@gmail.com
2)Dhruv Varshney     dhruvvarshney2612@gmail.com
3)LIkhith B           likhithlekhan@gmail.com
