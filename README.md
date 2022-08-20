# DA_AUSRainPrediction
Data Cleaning and developing Logistic Regression Model to predict Rains in Australia

# Introduction

Australia is the second driest continent in the world, with a mean annual rainfall of less than
600mm for more than 80 percent of Australia’s landmass. Even after these overall low
rainfalls, the westernmost part of Australia such as New South Wales, Queensland, and
Tasmania along with some parts of the Northern Territory suffer extreme flooding each year.
The dataset Rain in Australia consists of features that allow us to predict rainy days in
Australia. This kind of weather data is especially used by disaster management teams across
the world and has been proven advantageous in the past.


# Dataset Description
This dataset contains about 10 years of daily weather observations from 49 locations across
Australia. There are 23 columns and 145,460 rows.

# Driving Questions

Australia has the most frequent cases of natural calamities such as wildlife bushfires, severe
droughts, and floods in some coastal regions.
It would greatly assist the disaster management teams to manage these events if we could
predict rain, so we decided to ask questions that allow us to identify the significant
predictors to forecast rainy days in Australia.

Some of the questions we will be addressed along the way are as follow:
1. Which year and month has the most number of rainy days across Australia?
2. Which year and month observed the highest amount of rainfall?
3. Which state observed the highest amount of rainfall?
4. What are the significant variables in predicting next-day rain?
5. Select two locations based on the most rainy days and highest rainfall, then do some
comparisons using significant predictors identified in the previous section.

# Analysis

It included cleaning the dataset aand vizualizaing the data to answer the Driving Questions.

# Conclusion

Conclusion
Based on our analysis, we found out the following facts:
1. New South Wales is Australia’s wettest state based on the total amount of rainfall.
2. Based on our model fitting exercise, we know that Humidity3pm, Rainfall,
WindGustSpeed are the most important predictors to forecast a next-day rain in
Australia.
a. Recall that both models have very close accuracy scores: Model A 84.1% and
Model B 83.9%. In other words, the extra seven predictors we included in
Model A only managed to improve prediction by 0.2%.
3. In addition, visualizing using line plots is another way of identifying significant
predictors, albeit less accurate.

