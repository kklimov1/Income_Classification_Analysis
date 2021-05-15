# Income_Classification_Analysis
Task:
Determining wether or not someone is predicted to make over $50,000 annually, or not.

To see code, run analysis_clf.ipynb

In this project, we will analyze how different variables can affect the salary of an individual, and to reduce the feature set accordingly. We will then build Binary classifiers of increasing levels of complexity, ending with classifiers inputing into a custom Neural Net. The main goals are to: create an understanding of the circumstances in one's life that will correlate with a higher probability for him or her, of receiving a greater than $50,000 annual salary, and to analyze how various models perform in terms of precision, recall, accuracy, F1 score, ROC, and the AUC score.

Data used to create the code is in 'income_evaluation.csv

Notes:
To create this project, I used a pre-production version of Tensorflow, meant for the new M1 chip. Therefore not all of my packages were compatible. I was not able work entirely in one environment, so if you see execution counts, on the left side of the notebook, drop significantly, this was do to me changing environments.

The following files were used by me to save data while changing environments, and are not required on successful passthrough: 'clf_scores', 'test_set', 'clf_scores_complete', 'validation_set', 'training_set'

This notebook contains only my work. I have not copied any of the code, as all of it was written by me from scratch. Enjoy!
