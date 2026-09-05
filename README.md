# Mammography Image Analysis for Breast Cancer Detection
## About the Project

This project was developed as part of my Bachelor's thesis and focuses on the analysis of mammography images for breast cancer detection.
The image processing and classification pipeline uses Local Binary Patterns (LBP) for texture feature extraction and a Support Vector Machine (SVM) for classification.

## Technologies Used

- Python
- OpenCV
- NumPy
- Scikit-learn
- Matplotlib
- Local Binary Patterns (LBP)
- Support Vector Machine (SVM)

## Methodology

1. Mammography images are converted to grayscale and segmented using Otsu's thresholding method.
2. The breast region is identified and divided into smaller cells.
3. Local Binary Patterns (LBP) are used to extract texture features from the selected regions.
4. The extracted features are aggregated for each image.
5. A Support Vector Machine (SVM) with a polynomial kernel is used to classify the images as healthy or cancerous.
6. The model is evaluated using accuracy, precision, recall, F1-score and the ROC curve.

## Results

The model achieved approximately 72% accuracy on the test set.
The performance was also evaluated using precision, recall, F1-score and the ROC curve, with an AUC of approximately 0.67.

## Dataset

The dataset used for this project contains mammography images divided into two classes: healthy and cancerous.
The dataset is not included in this repository.

## Author

Alina Gabriela Tomoiaga
