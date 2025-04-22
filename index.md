---
layout: home
title: Dog Breed Classifier
nav_order: 1
---

A deep learning application that classifies dog breeds from images.

## About This Project

This dog breed classifier was developed as a demonstration of deep learning techniques for image classification.

## Features

- Upload an image of a dog and get its breed prediction
- Recognizes multiple dog breeds
- Shows confidence scores for predictions

## How It Works

The classifier uses a pre-trained ResNet model fine-tuned on dog breed images. The process involves:

1. Collecting images of different dog breeds
2. Training a deep learning model on these images
3. Using the trained model to classify new dog images

## Model Hosting

The trained model is hosted on Hugging Face Spaces at [https://huggingface.co/spaces/Nmloury/dog-breed-classifier](https://huggingface.co/spaces/Nmloury/dog-breed-classifier).

## Technologies Used

- FastAI: For deep learning model training
- PyTorch: The underlying deep learning framework
- Gradio: For creating the web interface

## Try It Out

Visit the [demo page](demo) to try the classifier.

## Credits

This project was inspired by the FastAI course and book. Special thanks to Jeremy Howard and the FastAI team.

## License

This project is licensed under the MIT License - see the LICENSE file for details.