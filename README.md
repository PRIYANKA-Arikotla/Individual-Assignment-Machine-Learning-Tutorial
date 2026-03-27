Decision Tree Overfitting Analysis
Overview:
This project investigates how tree depth affects the performance of a Decision Tree classifier. The objective is to demonstrate the concepts of underfitting and overfitting by analysing how model accuracy changes with increasing complexity.
The experiment uses a penguin dataset and evaluates model performance across different values of tree depth.

Objective:
To analyse the impact of the max_depth parameter on:

Training accuracy
Testing accuracy
Model generalisation

Dataset:

The dataset used in this project contains information about penguins, including:
Culmen length
Culmen depth
Flipper length
Body mass
Island
Sex
Species (target variable)

Methodology:

The following steps were performed:
Data preprocessing:
Handling missing values
Encoding categorical variables
Data splitting:
80% training set
20% testing set
Model training:
Decision Tree models trained with varying max_depth values
Evaluation:
Accuracy measured on both training and testing data
Results visualised using graphs

Results:
Training accuracy increases with tree depth
Testing accuracy improves initially but stabilises at higher depths
Overfitting occurs when the model becomes too complex

Visualisations included:
Accuracy vs Tree Depth graph
Shallow tree (underfitting)
Deep tree (overfitting)

References:
* Tutorials
*  Stack Overflow posts
*  lecture notes
