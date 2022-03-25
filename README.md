# Entertainment_project

To prepare the data for our Machine Learning model we must first start by importing our data into the model and creating a data frame.  Our team cleaned the data before importing it to better fit the model and produce more accurate results, since the data is pulled from a public website (www.Kaggle.com) we must ensure that we standardize the data to ensure the integrity of our analysis.  We found that the data was mainly in the Wrong Form and with some work could be standardized or repaired.  As an example, there were inconsistencies with the player column, and we decided to drop it since it would not have an impact on the outcome of our analysis. We then left joined another data set that included global sales to add another parameter for our model.
Feature engineering is an important part of the Machine Learning process as taking the time to apply the process will improve the quality of our results.  Some of the features that we will extract from the raw data include splitting our score column into tiers, adding an additional franchise column to show game success as a franchise as opposed to just per title.
Our data was split into the standard 80% training with 20% testing model, we believed this gave our model enough data to be properly trained.
In our selection of the machine learning model we came to the conclusion that a RandomForestClassifier was our best option. This is because RandomForestClassifiers handle low correlation data very well. Unfortunately many of our columns had low correlation or none at all, making this model ideal for our data. The limitations of this model is that it can only intake tabular data which led to our team adding the additional tier column from our scores.
