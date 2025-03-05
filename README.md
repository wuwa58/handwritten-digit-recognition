## Dataset source
https://archive.ics.uci.edu/dataset/80/optical+recognition+of+handwritten+digits

## Project Overview
This project aims to develop a supervised machine learning model for **Optical Recognition of Handwritten Digits**. The dataset is sourced from the **UCI Machine Learning Repository**, where handwritten digits from 43 different individuals were collected. The dataset consists of **64 features**, representing an 8x8 pixel image of a handwritten digit (0-9). However, the dataset is relatively small, which may impact model generalization. The goal is to classify these digits accurately using machine learning models.

## Result Summary
This project used the Optical Recognition of Handwritten Digits dataset to train SVM, KNN, and Random Forest models.
- **SVM** performed the best, achieving an accuracy of approximately **99%**.
- **Misclassification analysis** revealed that certain digits, such as `3` and `8`, were more challenging to distinguish.
- **Hyperparameter tuning** identified `C=10, gamma='scale'` as the optimal parameters for the SVM model.
- Future improvements could include using **CNN (Convolutional Neural Networks)** to enhance classification performance or applying **data augmentation** to improve model generalization.
