# Data Science and Machine Learning Assessment: Iris

For this assessment I had chosen the infamous Iris data set introduced by the British biologist Ronald Fisher in his paper “The use of multiple measurements in taxonomic problems”. This data set comprises of three different types of iris species (Setosa, Versicolour, and Virginica) stored in a 150x4 numpy.ndarray. The aim of this study is to understand the dataset, create statistical models to predict the species and finally justify those predictions. 
This project uses Jupyter Lab from Anaconda for Windows and Google Collab to ensure the code runs smoothly. 
To Run:
1.	Download Anaconda for appropriate PC type, and open Anaconda Navigator and launch Jupyter Lab and Notebook.
2.	Open new notebook and Import the Iris dataset from Scikit Learn using from sklearn.datasets import load_iris. Ensure Scikit learn is version 1.0 to avoid any errors in running the code.
3.	To access the Iris dataset from Scikit and download sample data go to: https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_iris.html#sklearn.datasets.load_iris
4.	Import libraries such as Numpy, Pandas, Seaborn, Scatter Matrix from pandas and train_test_split, matplotlib.pyplot, PCA, KMeans, GridSearchV, KNeighborsClassifier and ConfusionMatrixDisplay from sklearn. 
5.	To run each cell in jupyter notebook press ctrl + enter.
6.	Load Iris data using load_iris(), proceeding to coding iris.info(), iris.shape, iris.isnull().sum(), iris.describe() and iris.head() to gain information from data such as null entries, data type and statistical insights. Later iris[iris.duplicated()] is coded to find duplicates and iris_species.value_counts() to see if data is well balanced, despite the duplicates.
7.	Visual representation of the iris dataset is coded for using from sklearn.decomposition import PCA library, so we can see the different species designated according to sepal and petal sizes. 
8.	Moving further, a correlation graph and a scatter matrix were cons
