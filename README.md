# Real-time Facial Expression Recognition

This project proposes a deep CNN model for real-time facial expression recognition based on seven emotional classes: ‘neutral’, ‘happy’, ‘sad’, ‘angry’, ‘surprised’, ‘fear’, and ‘disgusted’. The model demonstrates strong generalization and classification performance.

## Project Overview

The model processes facial images to detect emotions accurately. Key steps include:
1. **Data Acquisition**: High-quality, well-classified databases were acquired.
2. **Preprocessing**: Face regions were detected, cropped, and converted into grayscale images to remove unnecessary information.
3. **Data Augmentation**: Techniques such as image rotation and scaling were used to increase the number and variation of training images, mitigating overfitting.
4. **Model Training**: The CNN model was trained using the FER2013 dataset, achieving a test accuracy of 83%.
5. **Class Balancing**: The Random Oversampling technique was applied to balance the dataset, significantly improving accuracy and reducing loss, particularly for the 'disgust' emotion.

## Features

- **Real-time Emotion Detection**: Capable of detecting seven emotional classes.
- **High Accuracy**: Achieved 83% test accuracy on the FER2013 dataset.
- **Data Augmentation**: Implemented to handle overfitting and improve model robustness.
- **Class Balancing**: Improved recognition of minority classes using oversampling techniques.

## Future Improvements

- **Facial Landmarks Detection**: Enhancing accuracy by utilizing facial landmarks for better alignment.
- **Pipeline Optimization**: Reducing misclassified emotions through pipeline improvements.
- **Multi-label Classification**: Handling images with multiple possible emotion labels to further refine the model's performance.

## Getting Started

To get started with the project, follow these steps:

### Prerequisites

- Python 3.x
- TensorFlow
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn

### Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/aitichomo/Real-time-Facial-Expression-Recognition.git]
   cd real-time-facial-expression-recognition
