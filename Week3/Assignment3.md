Link to repo: https://github.com/aditijoshi613/MLOps_Assignment

List of the preprocessing & feature engineering techniques that have been applied to the dataset:

1. Normalization(with z-score)

2. Split the training dataset into 80(train) and 20(validation) datasets

3. Applied **Synthetic Minority Oversampling Technique**(SMOTE) fror over sampling fraudulent transactions in order to take care of class imbalance.

4. Applied median and mode imputation methods on numerical and categorical data respectively.

F1 Scores of top 5 models before & after fine-tuning:

![image](https://user-images.githubusercontent.com/64677521/126666624-10cbee2d-9041-43c7-b328-36a9849dd5d5.png)

The Precision-Recall Plot & the Confusion Matrix for the blended model:

![image](https://user-images.githubusercontent.com/64677521/126667829-f091b521-bf1c-4e7d-a7a2-aaa6c3cca30d.png)

![image](https://user-images.githubusercontent.com/64677521/126667910-9830054b-8f50-4743-bf0b-8958f4a34a26.png)

Report the Accuracy, Precision, recall & F1-Scores of the blended model on your unseen test dataset:

Accuracy:	 0.9989

Precision:	 0.6579

Recall:	 0.7973

F1 Score:	 0.7209
