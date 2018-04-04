# CMPS 356 Datasets

Machine learning datasets used for CMPS 3560 AI at CSUB. These are (possibly) multi-class datasets intended for use by the backpropagation lab. These datasets were taken from the UCI Machine Learning Repository, a repository for publicly available datasets (<https://archive.ics.uci.edu/ml/index.php>). Generally, a sample consists of the feature vector followed by a 1-hot encoding of the class membership.

## iris.csv

Fishers iris dataset. "This is perhaps the best known database to be found in the pattern recognition literature. Fisher's paper is a classic in the field and is referenced frequently to this day. (See Duda & Hart, for example.)" (<https://archive.ics.uci.edu/ml/datasets/Iris>). 4 features, and 3 classes. The first 4 columns are measurements of the flower (petal, sepal) and the last 3 columns are a 1-hot encoding of the class membership. The 1-hot vector represents membership to Iris setosa, Iris versicolor and Iris virginica in that order.

## wine.csv

"These data are the results of a chemical analysis of wines grown in the same region in Italy but derived from three different cultivars. The analysis determined the quantities of 13 constituents found in each of the three types of wines" (<https://archive.ics.uci.edu/ml/datasets/Wine>). The first 13 columns are attributes of a wine, and the last 3 columns are a 1-hot encoding of the class membership. There are three possible categories of wine.
