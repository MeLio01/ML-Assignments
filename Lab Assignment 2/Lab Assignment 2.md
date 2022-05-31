I Illustrative exercises
1. (K-means) Download the old faithful dataset. It is instructive to understand the
origin of this dataset. Implement K-means (you cannot use the inbuilt library)
and recreate plots similar to Figure 9.1 and Figure 9.2 from Bishop’s book.
2. (K-means for Image segmentation / Image compression) Pick a suitable image
and apply clustering technique of the previous step to generate figures similar
to Figure 9.3 from Bishop’s book. Read about Image segmentation and Image
compression problems.
3. (Soft-assignment intuition) The objective of this exercise is to understand the
multivariate gaussian distribution.
(a) Refer to figure 2.23 in Bishop and generate the plots similar to that. As a
self study, explore how covariance matrix changes the contours.
(b) Generate 500 points from previous step clearing indicating the responsible
cluster. Thereafter, generate figure 9.5 from Bishop.
4. (GMM EM) Generate Figure 9.8 using the Old Faithful.
5. (Unsupervised labeling) This exercise concerns the classdemo.py file shared with
you. We saw that EM algorithm learnt the hidden parameters fairly well. This
question asks you to classify every point to each coin. Record the error rate of
this “classifier”.

  
II Exploratory exercises
1. (Auto labeling with EM) In practice, availability of labelled datasets is difficult.
One approach is to cluster the dataset suitably and then retrospectively assign
label to each cluster. Using the approach described in Figure 9.10 of Bishop
cluster the MNIST dataset into 10 clusters using mixture of bernoulli distribu-
tions and then examine the average cluster. Thereafter, each cluster is labelled
based on the average cluster. Record, how many points were misclassified based
on this approach.

2. See this lecture (upto slide 14) https://developers.google.com/machine-learning/crash-
course/classification/video-lecture. Design a bayes classifier (optimal) when
p0 = 0.95. Also class conditional densities for class 0 is normal mean 0 and
variance 1. For class 1, class conditional density is mean 1 and variance 1.
(a) FP for bayes classifier
(b) TP for bayes classifier
(c) Accuracy for bayes classifier
(d) For the same setup implement Neyman Pearson Classifier.
(e) Generate the ROC curve for various thresholds for the family of classifiers
which classify based on likelihood ratio and a threshold as done in Neyman
Pearson classifier.
(f) Implement max-min classifier

  
III Optional exercises for extra credit
1. Implement Bayes Classifier for the ‘MNIST Dataset’ by modeling class condi-
tional densities as
(a) Multivariate Gaussian distribution
(b) Multivariate Expoential distribution
2. Implement multinomial Naive Bayes classifier on ‘20 Newsgroups Dataset’.