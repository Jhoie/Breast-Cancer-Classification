# Breast-Cancer-Classification
A machine learning model that classifies cancer as benign or malignant

# INTRODUCTION
Breast cancer is the most common invasive cancer in women and the second leading cause of cancer death in women after lung cancer. It is a noteworthy health problem in today’s society. The early diagnosis of breast significantly improves the prognosis and chance of survival significantly, as it can promote timely clinical treatment to patients. Further accurate classification of benign tumors can prevent patients undergoing unnecessary treatments. Therefore, the accurate diagnosis of BC and classification of patients into malignant or benign groups is the aim of this machine learning model.

## Dataset
The dataset used in this model was created by Dr. William H. Wolberg, a physician at the University Of Wisconsin Hospital at Madison, Wisconsin, USA. To create the dataset Dr. Wolberg used fluid samples, taken from patients with solid breast masses and an easy-to-use graphical computer program called Xcyt, which is capable of perform the analysis of cytological features based on a digital scan. The program uses a curve-fitting algorithm, to compute ten features from each one of the cells in the sample, then it calculates the mean value, extreme value and standard error of each feature for the image, returning a 30 real-valuated vector.

### Attribute Information
Attribute Information:

1) ID number
2) Diagnosis (M = malignant, B = benign)
3) 
3-32) Ten real-valued features are computed for each cell nucleus:

a)radius (mean of distances from center to points on the perimeter)

b) texture (standard deviation of gray-scale values)

c) perimeter

d) area
e) smoothness (local variation in radius lengths)
f) compactness (perimeter^2 / area - 1.0)
g) concavity (severity of concave portions of the contour)
h) concave points (number of concave portions of the contour)
i) symmetry
j) fractal dimension ("coastline approximation" - 1)

The mean, standard error and "worst" or largest (mean of the three
largest values) of these features were computed for each image,
resulting in 30 features. For instance, field 3 is Mean Radius, field
13 is Radius SE, field 23 is Worst Radius.

All feature values are recoded with four significant digits.

Missing attribute values: none

Class distribution: 357 benign, 212 malignant

The dataset can be downloaded using any of these links. 
https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29
https://www.kaggle.com/uciml/breast-cancer-wisconsin-data?select=data.csv


# LIBRARIES
Numpy
Pandas
Matplotlib
Seaborn
Sklearn


# RESOURCES
I found the following resources helpful while working on this project.
https://towardsdatascience.com/building-a-simple-machine-learning-model-on-breast-cancer-data-eca4b3b99fa3
https://medium.com/datadriveninvestor/breast-cancer-detection-using-machine-learning-475d3b63e18e#
