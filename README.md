# passenger_satisfaction_stacking_anova
## by Lennart Wallentin, lennartwallentin@gmail.com 
In 'passenger_satisfaction_stacking_anova_lennart_wallentin.ipynb' I classify if a person flying with an unnamed north american airline company is satisfied or neutral/dissatisfied with their flight, but the classifying per se is not the end goal with this project instead the main objectives of this project are:

1. Is a Stacked Generalization (Stacking) model’s AUC score higher than two standalone (Logistic regression and XGBoost) machine learning model’s AUC scores?
2. Compare the three models through one-way analysis of variance (ANOVA) tests to see if they are different from each other.

In addition to that is my focus with this project to show that I have good knowledge regarding statistics, machine learning and business knowledge. I demonstrate that by explaining and using:
* <b>Statistics -</b> More advanced statistical topics as chi-square and construct a Cramer’s V tests for association between categorical features. GLM, the logistic function and odds ratio in conjunction with logistic regression. And as already mentioned one-way analysis of variance (ANOVA) tests. In addition basic statistics such as boxplots, Pearson correlation coefficient, histograms, probabilities etc is also part of this project.  


* <b>Machine learning -</b> Stacking using base and meta learners as well as Logistic regression and XGboost models and how they fit the data in regard to bias and variance. I cross-validate and do feature selection on all three models, and also hyperparameter tuning with Bayesian optimization on the standalone XGBoost and the XGBoost stacked base and meta learners. <br>A range of evaluation metrics are displayed with each model and since AUC is my main evaluation metric for this project, I construct graphs for each model that show the different cut off thresholds for the predicted probabilities in regard to True Positive Rate/Sensitivity and False Positive Rate.</br>


* <b>Business knowledge -</b> For example noticed that some of the survey questions are wrongly labeled as 0 instead of NA-value and fixed that. As for outliers I use business sense in regard to flight distance and departure delay outliers. Working in an organization I would of course talk to stakeholders to get even more information regarding any questions about the data.

The xlsx-file, ‘bayesian_optimization_iterations.xlsx’ contains all the Bayesian optimization iterations.
<br>The dataset that is used for this project is in the csv-file, 'data_passenger_satisfaction_stacking_anova_lennart_wallentin.csv'</br>
