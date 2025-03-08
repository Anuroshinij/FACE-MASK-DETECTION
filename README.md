# Face Mask Detection

This project detects whether a person is wearing a mask using a Convolutional Neural Network (CNN) and MTCNN for face detection.

## Dataset
- Kaggle dataset with two categories: `with_mask` and `without_mask`.

## Steps:
1. Preprocess images (normalization, augmentation).
2. Train a CNN model.
3. Use MTCNN for face detection in real-time.
4. Display results with bounding boxes (Green = Mask, Red = No Mask).

## How to Run
```bash
python detect_mask.py
