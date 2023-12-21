# Classification of Bloodcells Subtypes

## Basics

This is a Deep Learning based project where the task is to classify the subtype of Bloodcells from the given image using deep learning techniques.

## Project Description

This dataset contains 12,500 augmented images of blood cells (JPEG) with accompanying cell type labels. The cell types are Eosinophil, Lymphocyte, Monocyte, and Neutrophil. We use different pre-trained models named Resnet50, Modified Resnet50, EfficientNetb0, Xception to find the most accurate model. Furthermore, for explainibility we use Grad-CAM.  

![Grad-CAM](https://github.com/samanjoy2/bloodcells_detection/blob/main/gradcam.png?raw=true)

## Used

Datasets used: https://www.kaggle.com/datasets/paultimothymooney/blood-cells

- Models: 
- Resnet50          - Test Accuracy 88.21%
- Modified Resnet50 - Test Accuracy 89.42%
- EfficientNetb0    - Test Accuracy 77.48%
- Xception          - Test Accuracy 84.64%

![Accuracy](https://github.com/samanjoy2/bloodcells_detection/blob/main/scores.png?raw=true)
