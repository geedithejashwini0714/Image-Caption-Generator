# Image-Caption-Generator
# Image Caption Generator - Flickr 8k Dataset


# Project Information

The goal of this project is to predict captions for input images. The dataset contains 8,000 images, each paired with 5 captions. We extract features from both the images and their captions. These features are combined to predict the next word in a caption. A CNN is used for image feature extraction, while an LSTM is used for text feature extraction. The model's performance is evaluated using the BLEU score.


**Download link:** https://www.kaggle.com/adityajn105/flickr8k

**Environment:** Google Collab

# Libraries

- numpy
- matplotlib
- keras
- tensorflow
- nltk

# Neural Network

- VGG16 Network
- CNN-LSTM Network
  
**BLEU-1 Score:** 0.544
**BLEU-2 Score:** 0.319
