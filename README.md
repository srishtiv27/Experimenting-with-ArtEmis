# Experimenting with ArtEmis

This study was done as a part of the AI course offered by Indira Gandhi Delhi Technical University for Women, under Dr. Rishabh Kaushal.
Our team consists of the following members:
1. Srishti Vashistha
2. Rosalia Steffi Longjam
3. Priyanshi Sethi

## Aim
ArtEmis aims to solve the problem of emotion recognition and image
captioning on the WikiArt dataset. It contains a diverse set of artworks from all
across the world accompanied by utterances. The goal of ArtEmis is to bridge the
gap between machines and humans by allowing machines to react in a human-like
manner.

We have performed the following experiments:
* Transfer learning with ResNet 50 to extract features from our images.
* Applying KNN on 1000 images dataset.
* Applying Neural Network Architecture on 1000 images dataset.
* Applying Custom CNN Architecture on 1000 images and 2000 images dataset.
* Applying Custom CNN with L1/L2 regularization on 1000 images and 2000
images dataset.
* Applying Custom CNN with Dropout regularization on 1000 images and 2000
images dataset.
* Applying LSTM Model with 15 units on 455k annotations present in our dataset.
* Applying LSTM Model with 50 units on 455k annotations present in our dataset.
* Creating an Image Captioning model with feature extractor, LSTM sequence
model and a decoder.

## Dataset Statistics
The ArtEmis dataset is based on the WikiArt dataset, which is publicly available.
It includes 80,031 selectively chosen artworks created by 1,119 artists (as of 2015
download). The paintings fall under 27 different art styles. These art styles include
impressionism, abstract, and so on. They are also classified on the basis of 45
genres. The paintings can be assigned to portrait, and cityscape amongst others.
This further proves the richness and diversity of the ArtEmis dataset. 454,684
emotional responses and explanatory remarks were received by the annotators. The
final collection contains 37,250 unique words, as well as the descriptions provided
by 6,788 annotators who contributed a total of 11,138 hours to create it.

## Replicate our findings
You can go through these links in order to replicate our work.

### Preprocessing and visualizations
To show the visualizations and statistics on the original dataset, we ran a script
given by the authors of ArtEmis to get a preprocessed version of the ArtEmis
dataset.
The resulting analysis shows that the average token length is 15.92, the median
token length is 14.0 and the maximum token length is 207. The number of unique
paintings annotated is 80,031 and average annotators per painting is 5.68.
We also found the number of paintings which fall under a genre in the WikiArt
website. The reduced set of ArtEmis paintings which have a genre label are 361549.

### Code:
https://github.com/srishtiv27/Experimenting-with-ArtEmis/blob/master/ArtEmis_%20Visualisations.ipynb

### Milestone 1
For Milestone 1, we performed the following experiments:
* Transfer learning with ResNet 50 to extract features from our images.
* Applying KNN on 1000 images dataset.
* Applying Neural Network Architecture on 1000 images dataset.

### Code:
https://github.com/srishtiv27/Experimenting-with-ArtEmis/blob/master/M1_Artemis.ipynb

### Milestone 2
For Milestone 2, we performed the following experiments:
* Applying Custom CNN Architecture on 1000 images and 2000 images dataset.
* Applying Custom CNN with L1/L2 regularization on 1000 images and 2000
images dataset.
* Applying Custom CNN with Dropout regularization on 1000 images and 2000
images dataset.

### Code: 
https://github.com/srishtiv27/Experimenting-with-ArtEmis/blob/master/M2_Artemis_2000.ipynb

### Milestone 3
For Milestone 3, we performed the following experiments:
* Applying LSTM Model with 15 units on 455k annotations present in our dataset.
*  Applying LSTM Model with 50 units on 455k annotations present in our dataset.
* Creating an Image Captioning model with feature extractor, LSTM sequence
model and a decoder.

### Code:

* LSTM Model: https://github.com/srishtiv27/Experimenting-with-ArtEmis/blob/master/M3_Artemis.ipynb
* Image Captioning Model: https://github.com/srishtiv27/Experimenting-with-ArtEmis/blob/master/ImageCaptioningModelWithDuplicates.ipynb
