Projects for my intro to AI and Machine learning university courses, they are:
# Microproject 2:
Pyschiatric symptoms and diagnosis dataset, applied dimensionality reduction techniques(PCA),
cluster analysis with elbow curve, gap statistic, silhoutte analysis and dendrograms to find
the optimal number of clusters be used by clustering algorithms, then used agglomerative and
hierarchical clustering to find prevalent and ditinctive symptoms on patients and their 
relationship with their diagnosis.
# Microproject 3
Kidney problems dataset, we use biomarkers to predict the presence of kidney problems, it was
a small dataset, around 400 datapoints with many missing values, the project begins by doing
data cleaning, data wrangling and EDA to help the clasification models, for the missing values
we found that imputation worked well for our problem, for the classifier multiple techniques are
tested, first binary trees with cross validation on depth and criterion (gini, entropy), min samples
leaves and min samples split, then we tried gaussian naive bayes and naive bayes with binning
(feature discretization) obtaining 99% accuracy on both the training and test datasets.
# Microproject 4
Brain tumor detection and classification using CNN, we used tensorflow/keras to train a CNN from
scratch and transfer learning with the VGG16 model, obtaining a 95% accuracy on training and
84% in test.
# ML project
Drinking and smoking test predictions in korean national health insurance dataset, the project
consisted solving the multiclass and multiobjective classification problem on finding drinking
state (Y/N) and smoking state (drinker, quitted, never) on a relatively big dataset (>1M) rows,
we optimized the hamming loss using different techniques(XGBoost, random forest, binary multitrees)
but could only achieve an accuracy of 70%.
