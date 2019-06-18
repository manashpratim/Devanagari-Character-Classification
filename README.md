# Devanagari-Character-Classification
Classifying Images of Devanagari Characters
# Description
The goal of this project is to identify handwritten characters of Devanagari Script. The dataset consists of  92000 images of 32x32 pixel size corresponding to 46 characters. The dataset is available at https://web.archive.org/web/20160105230017/http://cvresearchnepal.com/wordpress/dhcd/. 
I have split the data into training and test sets at 90:10, each set having 82800 and 9200 images respectively. I have implemented a Convolutional Neural Network (CNN) using tensorflow and keras to classify the characters. The accuracies achieved in the training and validation sets after training for 10 epochs are 99.95% and 98.18% respectively.
