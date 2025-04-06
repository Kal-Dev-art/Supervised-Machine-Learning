# Supervised-Machine-Learning
I used various techniques to train and evaluate a model based on loan risk. Used a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

Purpose of the Analysis:
The goal of this analysis was to test how well a logistic regression model could predict whether a loan is healthy or high-risk. This helps the company decide if the model is reliable enough to use in real-life decision-making.

The Results:
Accuracy Score: The model was very accurate overall, especially at predicting healthy loans.

Precision Score:
* For healthy loans (Class 0): 1.00 – the model almost never incorrectly predicted a loan was healthy when it wasn’t.
* For high-risk loans (Class 1): 0.85 – 85% of the time, when the model said a loan was risky, it was right.

Recall Score:
* For healthy loans: 0.99 – it correctly found nearly all healthy loans.
* For high-risk loans: 0.91 – it caught 91% of the high-risk ones.

Summary & Recommendation:
The model did a great job predicting healthy loans and a decent job identifying high-risk loans. With high precision and recall, especially for healthy loans, the model could help reduce loan default risk. I would recommend using it, but suggest combining it with other tools or checks to improve the detection of high-risk loans even more.
