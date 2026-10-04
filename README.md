# PRODIGY_ML_04 - Hand Gesture Recognition

## Task
Develop a model to identify and classify different hand gestures from image data.

## Dataset
LeapGestRecog - Kaggle

## Approach
- Used 10 different hand gesture classes
- Selected 1,000 images
- Resized images to 64x64 grayscale
- Extracted HOG features
- Trained an SVM classifier using RBF kernel

## Results
- Total Images: 1,000
- Training Images: 800
- Testing Images: 200
- Number of Classes: 10
- Accuracy: 99.5%

## Gesture Classes
- Palm
- L
- Fist
- Fist Moved
- Thumb
- Index
- OK
- Palm Moved
- C
- Down

## Technologies
Python, NumPy, PIL, scikit-image, scikit-learn, Matplotlib, Seaborn
