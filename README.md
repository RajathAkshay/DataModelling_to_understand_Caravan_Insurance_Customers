# DataModelling_to_understand_Caravan_Insurance_Customers

# Introduction 

Nowadays, data is everywhere and in large scale. However, data is of no use if there is no one to analyse and extract knowledge from it. This assessment focuses on extracting knowledge from the car insurance data. Assume that you are a data analyst hired by a car insurance company, your task is to analyse the customer data collected by the car insurance company and use the knowl- edge from your analysis to help the company implement a targeted marketing strategy. In this assessment, you are going to analyse a car insurance data set, which is based on real world business data. The problem you are going to solve is: Can you • predict who would be interested in buying a caravan insurance policy? • explain why you make such a prediction? Describe the actual or potential customers; and explain why these customers buy a caravan policy.

# Dataset

The data set was previously used in a KDD data challenge and is freely avail- able online. It contains about 10K customer records, each of which have 86 attributes. The last attribute indicates if a customer actually bought the cara- van insurance. Those features have originally been discretised. It has been split into training and testing sets. The training set contains 5822 records, and the testing set contains 4000 records.
The training and testing files are stored in three different txt files below (click the hyper-line to download each txt file)
TICDATA2000.txt : Dataset to train and validate prediction models and build a description (5822 customer records). Each record consists of 86 at- tributes, containing socio-demographic data (attribute 1-43) and product ownership (attributes 44-86).The socio-demographic data is derived from zip codes. All customers living in areas with the same zip code have the same socio-demographic attributes. Attribute 86,“CARAVAN: Number of mobile home policies”, is the target variable, indicated by “V86” in the txt file.
TICEVAL2000.txt : Dataset for predictions (4000 customer records). It has the same format as TICDATA2000.txt, only the target is missing. Stu- dents are supposed to generate a list of predicted targets. All datasets are in tab delimited format. The meaning of the attributes and attribute values can be found in the data dictionary.
TICTGTS2000.txt Targets for the evaluation set.
In those datasets, each line corresponds to a record with tab delimited fields.
The name of the attribute contains a letter V followed by an integer that ranges from 1 to 86. Detailed data description can be found in the online
data dictionary
