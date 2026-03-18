# Task Title

MNIST Digit Recognition.

## Project Objective

The goal of this project is to build a model that can accurately identify handwritten digits from image data. The MNIST dataset contains grayscale images of digits, and a neural network is trained to classify them.

## Dataset

The dataset used is the MNIST dataset, built-in dataset available in TensorFlow/Keras and contains:

- 60,000 training images
- 10,000 testing images
- Image size: (28 × 28) pixels
- Each image represents a digit from 0 to 9.

## Tools and Libraries Used

- Python
- NumPy
- Matplotlib
- TensorFlow / Keras
- Scikit-learn
- Seaborn

## How the Model Works

1. The dataset is loaded and divided into training and testing sets.
2. Image data is normalized (pixel values scaled between 0 and 1).
3. Labels are converted into categorical format.
4. A neural network model is built using:
   - Flatten layer
   - Dense layers
   - Dropout (to prevent overfitting)
5. The model is trained using the Adam optimizer.
6. Performance is evaluated using accuracy and loss.

## Model Performance

- Training Accuracy: ~97%
- Validation Accuracy: ~97%
- Test Accuracy: ~97%

The model shows balanced performance with no overfitting.

## Visualizations

The project includes:

- Sample image visualization
- Training vs validation accuracy graph
- Training vs validation loss graph
- Confusion matrix heatmap

These visualizations help in understanding model performance.

## Evaluation

- Classification Report (Precision, Recall, F1-score)
- Confusion Matrix

The model performs well across all digit classes.

## Project Files

- `MNIST_Digit_Recognition.ipynb` -> Main notebook
- `mnist_digit_model.keras` -> Trained model
- `README.md` -> Project documentation

## Conclusion

In this project, a neural network model was successfully developed to recognize handwritten digits using the MNIST dataset. The model achieved high accuracy and demonstrated stable performance on unseen data.

## Author

Syeda Ather Fatima

This task is submitted as part of the **ARCH TECHNOLOGIES** Internship Program (Machine Learning Domain).
