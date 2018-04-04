# CMPS 356 Datasets

Machine learning datasets used for CMPS 3560 AI at CSUB. These are (possibly) multi-class datasets intended for use by the backpropagation lab. These datasets were taken from the UCI Machine Learning Repository, a repository for publicly available datasets (<https://archive.ics.uci.edu/ml/index.php>). Generally, a sample consists of the feature vector followed by a 1-hot encoding of the class membership.

## iris.csv

### Dataset Description

Fishers iris dataset. "This is perhaps the best known database to be found in the pattern
       recognition literature.  Fisher's paper is a classic in the field
       and is referenced frequently to this day.  (See Duda & Hart, for
       example.)  The data set contains 3 classes of 50 instances each,
       where each class refers to a type of iris plant.  One class is
       linearly separable from the other 2; the latter are NOT linearly
       separable from each other." (<https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.names>). 4 features, and 3 classes. The first 4 columns are measurements of the flower (petal, sepal) and the last 3 columns are a 1-hot encoding of the class membership. The 1-hot vector represents membership to Iris setosa, Iris versicolor and Iris virginica in that order.

### References
1. Fisher,R.A. "The use of multiple measurements in taxonomic problems", Annual Eugenics, 7, Part II, 179-188 (1936); also in "Contributions
      to Mathematical Statistics" (John Wiley, NY, 1950).
1. Duda,R.O., & Hart,P.E. (1973) Pattern Classification and Scene Analysis. (Q327.D83) John Wiley & Sons.  ISBN 0-471-22361-1.  See page 218.
1. Dasarathy, B.V. (1980) "Nosing Around the Neighborhood: A New System Structure and Classification Rule for Recognition in Partially Exposed      Environments".  IEEE Transactions on Pattern Analysis and Machine Intelligence, Vol. PAMI-2, No. 1, 67-71.
1. Gates, G.W. (1972) "The Reduced Nearest Neighbor Rule".  IEEE Transactions on Information Theory, May 1972, 431-433.
1. See also: 1988 MLC Proceedings, 54-64.  Cheeseman et al's AUTOCLASS II conceptual clustering system finds 3 classes in the data.

## wine.csv

### Dataset Description

"These data are the results of a chemical analysis of
      wines grown in the same region in Italy but derived from three
      different cultivars.
      The analysis determined the quantities of 13 constituents
      found in each of the three types of wines." (<https://archive.ics.uci.edu/ml/machine-learning-databases/wine/wine.names>). The first 13 columns are attributes of a wine, and the last 3 columns are a 1-hot encoding of the class membership. There are three possible categories of wine.

### References

1. Forina, M. et al, PARVUS - An Extendible Package for Data Exploration, Classification and Correlation. Institute of Pharmaceutical
       and Food Analysis and Technologies, Via Brigata Salerno, 16147 Genoa, Italy.
