# Food Image Classifier with Calorie Estimation

This project uses a pretrained deep learning model (MobileNetV2) to identify food items from images and estimate their calorie content. It's designed to help users track their dietary intake by simply uploading a food image.

## Features

- Image classification using **MobileNetV2**
- Predicts common food items like pizza, apple, burger, fries, etc.
- Estimates calorie content using a built-in calorie dictionary
- Visual output showing the food prediction and estimated calories

## Model

- **Model used**: `MobileNetV2` (pretrained on ImageNet)
- **Image input size**: 224×224
- **Prediction**: Top-1 food label
- **Calorie estimation**: Based on pre-defined calorie values

## Dependencies

- Python 3.x
- TensorFlow / Keras
- NumPy
- Matplotlib
- Google Colab (for interactive usage)

Install dependencies:

```bash
pip install tensorflow matplotlib
