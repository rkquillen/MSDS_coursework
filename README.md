# Master of Science in Data Science - CU Boulder


---

# Selected Coursework:

## Topic Modeling

[Nike shoe reviews analysis](#nike-shoe-reviews-analysis---topic-modeling) | Colab | YouTube

## Network Analysis

[Twitter marketing research](#twitter-marketing-research---network-analysis) | Colab | YouTube

## Text Classification

[BBC News article categorization](#bbc-news-article-categorization---text-classification) | Colab

[Disaster Tweets](#disaster-tweets---text-classification) | Colab

## Image Classification

[Histopathologic cancer detection](#histopathologic-cancer-detection---image-classification) | Colab

[Fashion-MNIST revisited](#fashion-mnist-revisited---image-classification) | Colab

[Fashion-MNIST](#fashion-mnist---image-classification) | Colab

## Image Style Transfer

[Monet](#monet---image-style-transfer) | Colab

<br>

---

---

### Nike shoe reviews analysis - (Topic modeling)
[View with Google Colab](https://colab.research.google.com/drive/1ZbZv8IGBOd0eWf_WiGc8hniIdlhYXRmW?usp=sharing)

[Watch presentation on YouTube](https://youtu.be/1QFWqZ6cgTE)

*Objective:*

Uncover product insights by analyzing a corpus of 5.7 million product ratings and reviews scraped from Amazon.com.  

*Techniques:*
- BERTopic
<br>

---

### Twitter marketing research - (Network analysis)
[View with Google Colab](https://colab.research.google.com/drive/1_JRhLvO0vbxj0SsCyKeStRpWHFBqWNeL?usp=sharing)

[Watch presentation on YouTube](https://youtu.be/6HtUowm_i5k)

*Objective:*

Gain marketing insights by conducting network analysis on a corpus of 175,000 Tweets mentioning Nike, Adidas, or Lululemon.  

Potential brand ambassadors were identified from a directed graph connecting users (nodes) via their mentions (edges).  Key words and topics associated with each brand were revealed by modeling word co-occurence as a directed graph.

*Techniques*
- Text preprocessing
- Sentiment analysis
- Directed graphs (with NetworkX and PyVis)
<br>

---

### BBC News article categorization - (Text classification)
[View with Google Colab](https://colab.research.google.com/drive/1Ta0MHvtIwaDo9EgRROOihVdPihiba7_J?usp=sharing)

*Objective:*

Build a model to classify BBC News articles as Business, Entertainment, Politics, Sports, or Technology.  The training dataset includes the headlines and full text of 1490 articles.

*Techniques:*
- Text preprocessing
- Tf-idf
- Non-negative Matrix Factorization (unsupervised learning)
- Complement Naive Bayes classifier
<br>

---

### Disaster Tweets - (Text classification)
[View with Google Colab](https://colab.research.google.com/drive/1luxiyGDyDVS-GhbBhk6G7SnndUVEBbJ9?usp=sharing)

*Objective:*

Build a model to identify Tweets indicating the occurrence of a genuine emergency.

Each of the 20,000 tweets in the dataset contain words associated with disasters, but the key words are often used in a non-literal context.  For example, "The sky is ablaze" may indicate a forest fire *or* describe a beautiful sunset.  Geo-tags, hashtags, mentions, emojis, and hyperlinks may be included in tweets.

*Techniques:*
- Text preprocessing
- GloVe embedding
- RNN
- LSTM
- BERT
<br>

---
### Histopathologic cancer detection - (Image classification)
[View with Google Colab](https://colab.research.google.com/drive/1fJA9XcmsS3agc_xWDTjZ4gOX6YH9JJLM?usp=sharing)

*Objective:*

Develop a model to detect the presence of metastatic cancer from microscope images of stained lymph node tissue samples.  The training set contains  220,025 labeled images (RGB color channels, 96x96 pixels).  

*Techniques:*
- Data augmentation
- CNN
<br>

---

### Fashion-MNIST revisited - (Image classification)
[View with Google Colab](https://colab.research.google.com/drive/1rRBCeWZve8BHZIEjek8n3nuGk_jIVQk-?usp=sharing)

*Objectives:*

Build a model to classify images of clothing items from 10 categories &mdash; T-shirts, trousers, pullovers, dresses, coats, sandals, shirts, sneakers, bags, and ankle boots.

The Fashion-MNIST dataset (70,000 grayscale images, 28x28 pixels) is an ideal sandbox for experimenting with hyperparameter tuning algorithms, cyclical learning rate schedules, data augmentation, and other model optimization techniques.  

*Techniques:*
- Data augmentation
- CNN
- Keras HyperBand tuner (hyperparameter optimization)
<br>

---
### Fashion-MNIST - (Image classification)
[View with Google Colab](https://colab.research.google.com/drive/1XZ9n1CblRWDQZblacbAlNW3cX6-XaReQ?usp=sharing)

*Objectives:*

Build a model to classify images of clothing items from 10 categories &mdash; T-shirts, trousers, pullovers, dresses, coats, sandals, shirts, sneakers, bags, and ankle boots.

This notebook focuses on utilizing unsupervised learning to build stand-alone models (K-Means, AggClustering) and as pre-processing (dimension reduction via PCA and SVD) for supervised models.

*Techniques:*
- *Decompostion:*
  - PCA
  - Truncated SVD
- *Clustering:*
  - Agglomerative Clustering
  - K-Means
- Gaussian Naive Bayes classifier
- Support Vector classifier
- Random Forest
<br>

---

### Monet - (Image style transfer)
[View with Google Colab](https://colab.research.google.com/drive/1e1oHw8U4eOEgf-bCI9l84MJyEGlge_Vc?usp=sharing)

*Objective:*

Create a model capable of altering photographs to look like Claude Monet's paintings.  

The dataset includes images of arbitrary photographs and Monet paintings. The training set does *not* contain paired images &mdash; i.e., photographs do *not* have direct Monet painting counterparts.

*Techniques:*
- CycleGAN
<br>
