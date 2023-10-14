# NLP-Projects
Classification of Tweets as Toxic and Non_Toxic, Kannada_Mnist using PCA


**Dataset**

Here I have used the Kannada MNIST dataset, which consists of handwritten digits in the Kannada script. The dataset is divided into training and testing sets, along with their corresponding labels. The dataset is loaded using the NumPy np.load function from the provided NPZ files.

Principal Component Analysis (PCA)

PCA is performed to reduce the dimensionality of the dataset. The code applies PCA with different numbers of components, and for each size, it trains and evaluates multiple classifiers.

**Classification Models**

The code trains and evaluates the following classifiers on the reduced feature set obtained from PCA:

Decision Tree Classifier
Random Forest Classifier
Naive Bayes Classifier (Gaussian Naive Bayes)
K-Nearest Neighbors (KNN) Classifier


**Summary**
These two projectcts help one's knowledge in using Count Vectoriser or Bag of Words, Tfidf Vectorser and PCA.

Since these two represent classification type problem i have used classification models like decision tree, Random Forest, K Neighbours, Naive Bayes..

The evaluation Metrics involve Classification Report which gives precison, accuracy and recall score, Confusion Matrix, and Roc-Auc score.

In Tweet Classification Several Models used and obtained an idea about which works better.

In Kannada Mnist different components(dimensions) used through PCA and Evaluated model's Performance..
