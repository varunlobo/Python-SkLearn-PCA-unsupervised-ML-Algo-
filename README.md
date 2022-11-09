# Python-SkLearn-PCA-unsupervised-ML-Algo-
This notebook demonstrates the use of PCA to reduce features in a dataset on lithium ion batteries obtained from kaggle.

## The purpose of this notebook is to demonstrate knowledge in the use of Principle Component Analysis (PCA) to reduce dimensionality of features, for visualization and classification.
## PCA is a widely used unsupervised Machine Learning algorithm 

![PCA vs LDA](https://user-images.githubusercontent.com/114509328/200872657-94ebbcca-55f6-4df2-b578-63e82ae2ece6.jpg)

The way PCA works, is the data is first projected along the axis where the variation is the highest. The data is first normalized and then the covariance of matrix is determined to identify highest eigen vector (EV). The EV corresponding to the lowest variation is then ignored. The hope is to capture the most variation while also reducing dimentionality. 

In our particular example, the PCA approach did not yield satisfactory results as you can see in the scatter plot below.

![PCA vs LDA scatter plot](https://user-images.githubusercontent.com/114509328/200873081-3b32e7e7-9c25-47fc-ae34-d43376eb8cce.jpg)
