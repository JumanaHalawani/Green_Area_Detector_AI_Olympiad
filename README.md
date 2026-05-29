# Green Area Detector AI Olympiad

An AI-powered satellite image analysis project that detects green areas Convolutional Neural Networks.  
The system divides an uploaded satellite image into grid cells, classifies each cell, and estimates the percentage of green area in the image.

## Project Overview

This project was created for the AI Olympiad. It uses a trained EfficientNet-based deep learning model to analyze satellite images and identify green spaces such as forests, crops, vegetation, pasture, rivers, and lakes.

The project includes:

- A trained image classification model
- A Streamlit web application
- A Colab notebook used for training
- The poster shown during the competition

## Features

- Upload a satellite image in JPG or PNG format
- Choose the grid resolution
- Classify each cell of the image
- Detect green and non-green regions
- Calculate total green area percentage
- Display a visual heatmap and analysis summary

## Technologies Used

- Python
- TensorFlow / Keras
- EfficientNet
- Streamlit
- NumPy
- Matplotlib
- Pillow
- EuroSAT Dataset

