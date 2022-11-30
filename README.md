# big_data_challenge
This is my solution to homework 22 for data bootcamp. I used the hint code that Dom provided for the class.


## Overview
For this challenge I looked at Amazon's data for toy sales and music sales. I used pyspark for this challenge as I connected the Amazon datasets to dataframes in my Colaboratory file. Once I had the files loaded I droped any na values and dupplicates. From there I created four new tables to match tables that I had created in pgAdmin. The tables in pgAdmin are in a database that is connected to AWS online. After creating these new tables in Colaboratory, I connected these tables to the databases in pgAdmin, connecting it to the databases in AWS.