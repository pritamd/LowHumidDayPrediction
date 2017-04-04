# LowHumidDayPrediction
This is an assignment from "Machine Learning With Big Data" Course from Coursera. This course is the fourth course for the Big Data Specializations.

Sensor measurements from the weather station were captured at one-minute intervals. These measurements were then processed to generate values to describe daily weather. Since this dataset was created to classify low-humidity days vs. non-low-humidity days (that is, days with normal or high humidity), the variables included are weather measurements in the morning, with one measurement, namely relatively humidity, in the afternoon. The idea is to use the morning weather values to predict whether the day will be low-humidity or not based on the afternoon measurement of relatively humidity.

This repository has both KNIME Workspace and Jupyter Python Notebook for Spark.

I used KNIME to compare the low humid day prediction learning model for Decision Tree, kNN (k = 3) and Naive Bayes. The data is very contradictory and confusing. For example, Decision Tree had best accuracy with 80% train data, kNN (k = 3) had best accuracy with 90% train data and Naive Bayes had best accuracy with 70% train data.

Here is the detail information:

![alt tag](https://github.com/pritamd/LowHumidDayPrediction/blob/master/algocompare.PNG)
