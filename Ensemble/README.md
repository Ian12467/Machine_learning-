## Heterogeneous 
* Preprocessing: Both datasets were preprocessed by removing unwanted columns (CustomerId in churn and children in insurance) that did not play a significant role in the analysis of the data. No missing values were identified in either dataset.

* Test/Training Split: The datasets were split into test and training sets using a 0.2 test fraction.

* Ensemble Classifier: A heterogeneous ensemble classifier was created using three base classifiers - RandomForestClassifier, DecisionTreeClassifier, and LogisticRegression - and a VotingClassifier with a hard voting scheme. The random forest classifier had 50 estimators, while the decision tree classifier had a maximum depth of 5.

* Evaluation Metrics: The performance of the models was evaluated using accuracy, precision, recall, and F1 score. Higher accuracy values indicate that the models performed efficiently on the dataset, while lower accuracy values indicate poor ensemble on the dataset.

* Churn Model vs. Insurance Model: The churn model produced various results with high accuracy, indicating a good ensemble was achieved, while the insurance model produced average values
