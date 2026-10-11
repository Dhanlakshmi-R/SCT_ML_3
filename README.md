# Task 3: Cat vs Dog Image Classification using SVM

## Objective
To build a machine learning model that classifies images as cats or dogs using a Support Vector Machine (SVM).

## Dataset
Microsoft Cats and Dogs dataset:
https://www.microsoft.com/en-us/download/details.aspx?id=54765

The project uses up to 1,000 cat images and 1,000 dog images.

## Technologies Used
- Python
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Methodology
1. Load and preprocess the cat and dog images.
2. Convert images to grayscale and resize them to 32 × 32 pixels.
3. Flatten images into numerical feature vectors.
4. Split the data into training and testing sets.
5. Standardize features using StandardScaler.
6. Reduce dimensionality using PCA.
7. Train an SVM classifier with an RBF kernel.
8. Evaluate the model using accuracy, classification report, and confusion matrix.
9. Test predictions on a new image.

## Results
- Training and testing split: 80:20
- Model accuracy: Add the actual percentage obtained from the notebook.
- Evaluation: See the confusion matrix and sample prediction images.

## Conclusion
This project demonstrates image preprocessing, dimensionality reduction, SVM training, and evaluation for binary image classification.
