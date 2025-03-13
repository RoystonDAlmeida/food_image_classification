# Food Image Classification using Transfer Learning

This project demonstrates how to build an image classification model for the Food-101 dataset using transfer learning with TensorFlow and Keras.

## Project Overview

The Food-101 dataset contains 101 food categories with 1000 images per category. This project utilizes transfer learning by leveraging the pre-trained EfficientNetB0 model to achieve high accuracy in classifying food images.

## Dependencies

- TensorFlow 2.12.0
- TensorFlow Hub
- Pillow
- TensorFlow Datasets
- Matplotlib

## Installation

1. Clone the repository:
```bash
git clone git@github.com:RoystonDAlmeida/food_image_classification.git
```

2. Navigate to the folder:
```bash
cd food_image_classification/
```

## Usage

1. Open the Jupyter Notebook or Google Colab file containing the code.
2. Execute the code cells sequentially to:
    - Load the Food-101 dataset.
    - Preprocess the data and apply data augmentation.
    - Build the model using transfer learning with EfficientNetB0.
    - Compile and train the model.
    - Evaluate the model's performance.
    - Visualize the training history.

## Methodology

- **Transfer Learning:** The project utilizes the pre-trained EfficientNetB0 model as a base, fine-tuning it for the Food-101 dataset.
- **Data Augmentation:** Random flipping and rotation are applied to the training images to improve model generalization.
- **Mixed Precision Training:** Mixed precision training is used to speed up training and reduce memory usage.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.
