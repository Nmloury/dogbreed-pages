---
layout: page
title: Demo
nav_order: 3
---

# Dog Breed Classifier Demo

## Try the Classifier

Below is a demo of the dog breed classifier. You can upload an image of a dog, and the model will predict its breed.

<div class="demo-container">
  <iframe src="https://nmloury-dog-breed-classifier.hf.space" width="100%" height="600" frameborder="0"></iframe>
</div>

## How to Use

1. Upload an image of a dog
2. Click "Submit"
3. View the predicted breed and confidence score

## Example Predictions

Here are some example predictions from the classifier:

| Dog Image | Predicted Breed | Confidence |
|-----------|-----------------|------------|
| ![Golden Retriever](assets/images/golden_retriever.jpg) | Golden Retriever | 98% |
| ![Pitbull](assets/images/pitbull.jpg) | Pitbull | 95% |
| ![Pug](assets/images/pug.jpg) | Pug | 97% |
| ![Cattle Dog](assets/images/cattle_dog.jpg) | Cattle Dog | 96% |
| ![Weimaraner](assets/images/weimaraner.jpg) | Weimaraner | 94% |

## Tips for Best Results

- Use clear, well-lit images of dogs
- Ensure the dog is the main subject of the image
- Try to capture the dog's face and body clearly
- Avoid images with multiple dogs or other animals
- Use images where the dog is in a natural pose

## Limitations

The current version of the classifier has some limitations:

- It can only recognize the five breeds it was trained on
- It may struggle with mixed breeds
- Image quality and lighting can affect accuracy
- Unusual poses or angles may reduce confidence
- The model may be confused by similar-looking breeds 