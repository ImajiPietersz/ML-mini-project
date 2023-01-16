Credit default prediction is central to managing risk in a consumer lending business. Credit default prediction allows lenders to optimize lending decisions, which leads to a better customer experience and sound business economics. Current models exist to help manage risk. But it's possible to create better models that can outperform those currently in use.

American Express is a globally integrated payments company. The largest payment card issuer in the world, they provide customers with access to products, insights, and experiences that enrich lives and build business success.

In this project, you’ll apply your machine learning skills to predict credit default. Specifically, you will leverage given dataset to build a machine learning model that challenges the current model in production. Training, validation, and testing datasets include time-series behavioral data and anonymized customer profile information. You're free to explore any technique to create the most powerful model, from creating features to using the data in a more organic way within a model.

Dataset

The dataset contains aggregated profile features for each customer at each statement date. Features are anonymized and normalized, and fall into five general categories:

D_* = Delinquency variables
S_* = Spend variables
P_* = Payment variables
B_* = Balance variables
R_* = Risk variables
For example: ['B_30', 'B_38', 'D_114', 'D_116', 'D_117', 'D_120', 'D_126', 'D_63', 'D_64', 'D_66', 'D_68']

Competition URL:  https://www.kaggle.com/competitions/amex-default-prediction/overview


Task

You should build a machine learning model that can predict if a customer will leave the service, given the attributes for that customer for the previous month.

You should:

Identify and/or create relevant features
Try out at least 3 approaches, two of them should be kNN and SVM
Validate the results
Select the best performing model using sensible criteria. (The final score in the Kaggle competition should come from this model)
Write a short paper using IEEE conference paper guidelines. This should be written using Latex and should be 6 pages long as in IEEE format. The paper should also be submitted to the conference link
Please use your index number as the username in the following format when creating your Kaggle account: UOM_IndexNo (E.g.: UOM_190001X)

Grading Criteria

Feature engineering [20 points]
Implementation of at least 3 supervised learning methods to solve the problem and the performance of the best model [30 points] (You should at least include KNN and SVM in the set of 3 methods you try out)
Validation of the results and the selection of the best performing model [20 points]
Short paper (6 pages) [30 points]
Paper format

Written using LateX (For LateX template: https://www.ieee.org/conferences/publishing/templates.html)
should adhere to IEEE conference paper guidelines
The copyright note at the bottom of the front page should be: CS3110/2022//
