# Building-Machine-Learning-Pipelines-using-Pyspark

In this project I show how create machine learning pipelines using Python and Spark, free, open-source programs that I downloaded.
I have used a dataset (CSV file) which contain several mechanical features of different car models.
I loaded this data in Spark in order to perform basic cleaning techniques such as removing columns with high missing values and removing rows with missing values. 
After this step of data preparation, I created a machine learning pipeline with a random forest regression model. A cross validation used and parameter tuning to select the best model from the pipeline.
 Lastly, an evaluation part of model’s performance using necessary metrics.
 
The main steps of the project are listed below:
1.	Install Spark on Google Colab and load a dataset in PySpark
2.	Describe and clean the dataset
3.	Create a Random Forest pipeline to predict car prices
4.	Create a cross validator for hyperparameter tuning
5.	Train your model and predict test set car prices
6.	Evaluate the model’s performance via several metrics
