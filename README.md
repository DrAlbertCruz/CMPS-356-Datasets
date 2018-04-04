# CMPS 356 Datasets

Machine learning datasets used for CMPS 3560 AI at CSUB. These are (possibly) multi-class datasets intended for use by the backpropagation lab. These datasets were taken from the UCI Machine Learning Repository, a repository for publicly available datasets (<https://archive.ics.uci.edu/ml/index.php>). Generally, a sample consists of the feature vector followed by a 1-hot encoding of the class membership.

## iris.csv - Fisher's iris dataset

### Dataset Description

> "This is perhaps the best known database to be found in the pattern recognition literature.  Fisher's paper is a classic in the field        and is referenced frequently to this day.  (See Duda & Hart, for example.)  The data set contains 3 classes of 50 instances each,        where each class refers to a type of iris plant.  One class is linearly separable from the other 2; the latter are NOT linearly
       separable from each other." (<https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.names>). 
       
The purpose of this dataset is to predict the type of Iris flower. There are 4 features, and 3 possible classe memberships. The first 4 columns are measurements of the flower (petal, sepal) and the last 3 columns are a 1-hot encoding of the class membership. The 1-hot vector represents membership to Iris setosa, Iris versicolor and Iris virginica in that order. Because of linear separability you should get very close to 100% even without a non-linear classifier.

### Reference
1. Fisher,R.A. "The use of multiple measurements in taxonomic problems", Annual Eugenics, 7, Part II, 179-188 (1936); also in "Contributions
      to Mathematical Statistics" (John Wiley, NY, 1950).

## wine.csv - Wine Data Set

### Dataset Description

"These data are the results of a chemical analysis of wines grown in the same region in Italy but derived from three       different cultivars. The analysis determined the quantities of 13 constituents found in each of the three types of wines." (<https://archive.ics.uci.edu/ml/machine-learning-databases/wine/wine.names>). 

This purpose of this dataset is to detect the type of wine. The first 13 columns are attributes of a wine, and the last 3 columns are a 1-hot encoding of the class membership. There are three possible categories of wine.

### Reference

1. Forina, M. et al, PARVUS - An Extendible Package for Data Exploration, Classification and Correlation. Institute of Pharmaceutical
       and Food Analysis and Technologies, Via Brigata Salerno, 16147 Genoa, Italy.
       
## breastcancer.csv - Breast Cancer Wisconsin (Diagnostic) Data Set

### Dataset Description

> "Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.  They describe characteristics of the cell nuclei present in the image. A few of the images can be found at <http://www.cs.wisc.edu/~street/images/>.

> Separating plane described above was obtained using Multisurface Method-Tree (MSM-T). K. P. Bennett, "Decision Tree Construction Via Linear Programming." Proceedings of the 4th Midwest Artificial Intelligence and Cognitive Science Society, pp. 97-101, 1992], a classification method which uses linear programming to construct a decision tree. Relevant features were selected using an exhaustive search in the space of 1-4 features and 1-3 separating planes.

> The actual linear program used to obtain the separating plane in the 3-dimensional space is that described in: K. P. Bennett and O. L. Mangasarian: "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34" (<https://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin/wdbc.names>).
       
The purpose of this dataset is to predict if a breast tumor is malignant or benign. The first ten columns are attributes of the tumor and the last two columns are a 1-hot vector indicating the class membership. There are two classes (malignant or benign).

### Reference
1. W.N. Street, W.H. Wolberg and O.L. Mangasarian 
	Nuclear feature extraction for breast tumor diagnosis.
	IS&T/SPIE 1993 International Symposium on Electronic Imaging: Science
	and Technology, volume 1905, pages 861-870, San Jose, CA, 1993.

