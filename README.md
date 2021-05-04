## Sentiment-Analysis-on-IMDB-Dataset

### Sentiment analysis

- Sentiment analysis is the process of detecting positive or negative sentiment in text. It’s often used by businesses to detect sentiment in social data, gauge brand reputation, and understand customers.

## Dataset Used

<p align="center">
<img src = "https://user-images.githubusercontent.com/48115585/116819261-f63e9600-ab8c-11eb-9d53-80031a8436e9.png" width="700" height="350" />
</p>


This is a dataset for binary sentiment classification containing substantially more data than previous benchmark datasets. We provide a set of 25,000 highly polar movie reviews for training, and 25,000 for testing.

## Implementation

The implementation was based on a research paper [Sentiment Analysis on Movie Review Data Using Machine Learning Approach](https://github.com/Chirag-Shilwant/Sentiment-Analysis-on-IMDB-Dataset/blob/main/paperSMAI.pdf).

## Classifiers Implemented
1. Multinomial Naive Bayes(MNB)
2. Support Vector Machine(SVM)
3. Maximum Entropy(ME)
4. Decision Tree(DT)
5. Gaussian Naive Bayes(GNB)
6. Convolutional Neural Network (CNN)

## Text Representation Models implemented
1. Bag of Words
2. Word2vec

## Accuracy obtained using Bag of Words Model
| Classifiers   | Accuracy   |
| --------------|:----------:|
| MNB           |   85.42%   | 
| SVM           |   83.36%   |   
| ME            |   88.46%   |
| DT            |   73.40%   |
| GNB           |   84.60%   |


## Accuracy obtained using Word2vec Model
| Classifiers   | Accuracy   |
| --------------|:----------:| 
| SVM           |   84.60%   |   
| ME            |   85.46%   |
| DT            |   69.04%   |
| CNN           |   86.19%   |
