# Image-Classification-and-Reverse-Image-Search-on-Google-Open-Image-Dataset

The primary goal we strived to achieve is the ability to process large amounts of data and convey the results of our analysis through informative visualizations.
We used the UMBC Big Data Cluster to classify images of animals and birds using the MobileNet pre-trained model. We calculated accuracies for each label and plotted
the distribution. Later, we performed Reverse Image Search and Image Ranking. 

About the Dataset:
Google Open Image Dataset. This dataset consists of 9 million images divided into 15,387 classes. The dataset is split into a training set (9,011,219 images),
a validation set (41,620 images), and a test set (125,436 images). Since we are using only a subset of this data, the size of the dataset is around 500 GB.

Initially, before starting our analysis, we tried exploring the dataset to gain some meaningful insights into the data that could help us along the course of the project.
We started by setting up HDFS, initializing Spark, setting our environment configuration, creating directories for weight files in our directory, installing packages like 
tensorflow, keras applications, spark.sql functions, numpy, pandas, matplotlib, os, etc. We used the class_descriptions_boxable.csv from metadata, image label data from 
labels.csv, the images.parquet file, and the bounding boxes data (test, train and validation) from the HDFS for our analysis.

This project includes exploratory analysis on different labels and their respective bounding boxes count, Acuuracy scores of different cats when trained using Mobilenet,
Ranking of Images using PPI(pixels per inch), Reverse image search.


