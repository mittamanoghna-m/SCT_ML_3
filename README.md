# Cats vs Dogs Classification using SVM

## SkillCraft Technology - Task 3

### Objective

Build an image classification model that can distinguish between cat and dog images using Machine Learning.

## Algorithm Used

- Support Vector Machine (SVM)


## Tools & Libraries

- Python
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn

## Dataset

Cats and Dogs Dataset

Classes:
- Cat
- Dog

## Process

1. Loaded cat and dog images from the dataset.
2. Converted images to grayscale.
3. Resized images to 50×50 pixels.
4. Flattened images into feature vectors.
5. Split data into training and testing sets.
6. Trained a Support Vector Machine (SVM) classifier.
7. Evaluated model performance using accuracy score and classification report.
8. Visualized predicted and actual labels on test images.

## Results

Dataset Loaded Successfully

- Total Samples: 275 Images
- Feature Size: 2500
- Classes: Cat, Dog

Accuracy Achieved: **41.8%**

Classification metrics:

- Precision
- Recall
- F1-Score

Visual predictions were generated to compare predicted labels with actual labels on test images.

## Sample Output

Examples:

- Predicted: Cat | Actual: Cat
- Predicted: Dog | Actual: Dog
- Predicted: Cat | Actual: Dog
- Predicted: Dog | Actual: Cat


## Conclusion

The SVM classifier was successfully implemented for binary image classification of cats and dogs. The model was able to learn image patterns and generate predictions on unseen test images. Visual outputs were produced to demonstrate classification performance.

## Author

Manoghna

SkillCraft Technology Machine Learning Internship
