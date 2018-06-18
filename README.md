## Boston-houses-prediction
This work contains a set of different models, that predict the price of Boston houses for Kaggle completion.

Short description of the dataset, that was used ():

| Feature     | Description                        | Type    | Example             |
|-------------|------------------------------------|---------|---------------------|
|       |          ||    |
| **  |        |   |         |
| **      |  | |  |
| ** |  |  |                    |


### Outcome binary-classes models metrics:

| Model name                  | Accuracy | Precision | Recall | F-measure |
|-----------------------------|----------|-----------|--------|-----------|
| Logistic regression         | 91 %     | 91 %      | 91 %   | 91 %      |
| Bagged decision tree        | 90 %     | 90 %      | 90 %   | 90 %      |
| KNN classifier with 9 NN    | 89 %     | 91 %      | 90 %   | 90 %      |
| Random forest with 70 trees | 90 %     | 89 %      | 90 %   | 89 %      |
| Linear regression           | 82 %     | 91 %      | 88 %   | 89 %      |
| KNN classifier with 3 NN    | 80 %     | 89 %      | 84 %   | 85 %      | 
| Decision tree               | 76 %     | 82 %      | 76 %   | 79 %      | 


### Outcome regression models metrics:
| Model name                                                         | Accuracy |
|--------------------------------------------------------------------|----------|
| Basic linear regression, 1000 iterations                           | 84 %     |
| Linear regression without 'zn' and 'nox' features, 1000 iterations | 82 %     |
| Linear regression without 'zn' and 'nox' features                  | 79 %     |
| Linear regression without 'zn' feature                             | 76 %     |
| Basic linear regression                                            | 73 %     |
| Linear regression using 'ID' feature                               | 70 %     |
