# KNN-LDA-QDA-and-Logistic-Classification-in-R
Running  QDA, LDA, KNN and Logistic Classification models on insurance data to predict whether a person is a smoker or not. 
Code is written in R using R Markdown and knits to an html documument. 
Models are built on the tidymodels framework. 
Plots are built in ggplot.

--- Analysis
The highest performing model was the KNN model with n = 5 and explanatory variables "charges", "age", and "bmi". The accuracy of this model was around 98.5%. 
The QDA and LDA models performed sligtly worse with an accuracy rate of around 92%. 
The logistic classification model performed very well with an accuracy rate around 98%.


