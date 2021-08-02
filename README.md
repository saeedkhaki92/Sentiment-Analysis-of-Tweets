# Sentiment-Analysis-of-Tweets

The goal of this project is to perform sentiment analysis of tweets. The project uses Trax deep learning library for implementation. I also implemeneted the model in Tensorflow for comparision. 


## Getting Started

### Dependencies

Following packages should be installed on python 3:

- Trax
- numpy
- random

<a href="https://github.com/google/trax" target="_blank">Trax</a> is an end-to-end library for deep learning that focuses on clear code and speed. It is actively used and maintained in the Google Brain team. It is faster than Tensorflow and Pytorch and also the codes are more clear. It also supprts both TPUs and GPUs.


## Dataset

The model is trained and validated on 10K tweets. I used 8K tweets for training and 2K tweets for validation.


### Model

The model uses an embedding layer to convert sparse encoding of the inputs to dense vector representations. Then, the dense encodings go to the classifer for classification. The model architucture is as follows:


![Alt Text](https://github.com/saeedkhaki92/Sentiment-Analysis-of-Tweets/blob/main/nn.jpg)

