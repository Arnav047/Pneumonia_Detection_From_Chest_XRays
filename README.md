# Pneumonia_Detection_From_Chest_XRays

## Problem Statement
* Build a binary classifier to detect pneumonia using chest x-rays.

### Pneumonia
* Pneumonia Pneumonia is an infection that inflames the air sacs in one or both lungs. The air sacs may fill with fluid or pus (purulent material), causing cough with phlegm or pus, fever, chills, and difficulty breathing. 

### DataSet Description
* The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,800 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal). Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care. For the analysis of chest x-ray images, all chest radiographs were initially screened for quality control by removing all low quality or unreadable scans. The diagnoses for the images were then graded by two expert physicians before being cleared for training the AI system. In order to account for any grading errors, the evaluation set was also checked by a third expert.

## Proposed Solution:
* Created CNN model using Tensorflow to classify chest X rays as Pneumonia or normal by dealing with Dataset of 5800 images.
* Identifying and detecting pneumonia from the Chest X Rays using the ResNet Architecture and achieved an Accuracy of 75%
