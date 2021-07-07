# Vaccine Trends Analyzing System<br>

## Abstract<br>
In times of covid, as the number of cases are increasing day by day, the only ray of hope is vaccines. Thus, we have designed a system which aims to analyze various trends related to vaccination. The system will be used to predict the amount of vaccines distributed in future. Also we can classify the locality into zones according to its population, number of cases active and number of people vaccinated at a particular locality. We also cluster these localities according to the population and number of people vaccinated. <br>
## Algorithms<br>
1.  Simple Linear Regression Algorithm - Simple linear regression is a statistical method that allows us to summarize and study relationships between two continuous variables. Here, the two variables are, the day and amount of vaccines distributed in the locality. Thus, using regression, we can predict the future values according to the previous trends in distribution of vaccines.
2. Random Forest Regression Algorithm - Random Forest Regression is a supervised learning algorithm that uses ensemble learning method for regression. Thus we tried using this too for the same dataset of days and the amount of vaccines distributed. It gives a more accurate prediction of the amount for the future.
3. Decision Tree Algorithm - Decision Tree Algorithm is used to create a training model that can use to predict the class or value of the target variable by learning simple decision rules inferred from training data. Here, the training data consists of 3 attributes - population of a locality, no of active cases in that locality and the number of people vaccinated. We finally classify them into two zones according to the attributes values.
4. Naive Bayes Algorithm - Naive Bayes is a simple classifying algorithm using the naive bayes theorem. We again used the same dataset as decision tree to classify the data. But we obtained a lower accuracy using naive bayes algorithm.
5. Support Vector Machine Algorithm - The Support Vector Machine Algorithm classifier is a frontier which best segregates the two classes using the hyper-plane. Thus, we used this algorithm to increase our accuracy in classifying the data. The dataset was same consisting of population of a locality, no of active cases in that locality and the number of people vaccinated. 
6. K Means Algorithm - K-means is a centroid-based algorithm, where we calculate the distances to assign a point to a cluster. The dataset consists of the population number of various localities and the number of people vaccinated at the locality. It forms to two clusters according to our dataset. 

## Dataset 
There are two files in the repository consisting of regression, classification and clustering dataset.

## Implementation 
The given algorithms are implemented in python and are uploaded in the repository.

## Accuracy
We obtained an accuracy of 70 % using Naive Bayes algorithm for classification of data. Whereas SVM and Decision Tree Algorithm both gave about 77% accuracy on our dataset.
We can't obtain the accuracy of clustering and regression algorithms.

## Results
In times of covid, our system will help the people in analyzing the trends in vaccine distribution and identify the hotspots in the localities. It aims to provide efficient analysis using real time dataset, in the real world. The system provides a accuracy of about 77%. 
