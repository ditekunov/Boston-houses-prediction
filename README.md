## Boston-houses-prediction
This work contains a set of different models, that predict the price of Boston houses for Kaggle completion.

Short description of the dataset, that was used (https://www.kaggle.com/c/boston-housing):

| Feature     | Description                                                     | Type    | Example             |
|-------------|-----------------------------------------------------------------|---------|---------------------|
| *crim*      | per capita crime rate by town.                                  | Numeric | 0.00632                    |
| *zn*        | proportion of residential land zoned for lots over 25,000 sq.ft.| Numeric | 18                    |
| *indus*     | proportion of non-retail business acres per town.               | Numeric | 2.31                    |
| *chas*      | Charles River dummy variable                                    | Boolean | 0                  |
| *nox*       | nitrogen oxides concentration (parts per 10 million).           | Numeric | 538                   |
| *rm*        | average number of rooms per dwelling.                           | Numeric | 6575                   |
| *age*       | proportion of owner-occupied units built prior to 1940.         | Numeric | 65.2                   |
| *dis*       | weighted mean of distances to five Boston employment centres.   | Numeric | 4.09                   |
| *rad*       | index of accessibility to radial highways.                      | Numeric | 1                   |
| *tax*       | full-value property-tax rate per $10,000.                       | Numeric | 296                   |
| *ptratio*   | pupil-teacher ratio by town.                                    | Numeric | 15.3                   |
| *black*     | 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town. | Numeric | 396.9                   |
| *lstat*     | lower status of the population (percent).                       | Numeric | 4.98                   |
| *medv*      | median value of owner-occupied homes in $1000s.                 | Numeric | 24                   |



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


### Outcome 10-classes models metrics:

| Model name                  | Accuracy | Precision | Recall | F-measure |
|-----------------------------|----------|-----------|--------|-----------|
| Random forest with 580 trees| 58 %     | 72 %      | 58 %   | 62 %      | 
| Bagged decision tree        | 55 %     | 69 %      | 55 %   | 59 %      | 
| KNN classifier with 3 NN    | 50 %     | 71 %      | 48 %   | 56 %      |
| Logistic regression         | 43 %     | 55 %      | 43 %   | 46 %      |
| Linear regression           | 73 %     | 41 %      | 31 %   | 30 %      |
| Decision tree               | 36 %     | 40 %      | 36 %   | 35 %      |



### Outcome regression models metrics:
| Model name                                                         | Accuracy |
|--------------------------------------------------------------------|----------|
| Basic linear regression, 1000 iterations                           | 84 %     |
| Linear regression without 'zn' and 'nox' features, 1000 iterations | 82 %     |
| Linear regression without 'zn' and 'nox' features                  | 79 %     |
| Linear regression without 'zn' feature                             | 76 %     |
| Basic linear regression                                            | 73 %     |
| Linear regression using 'ID' feature                               | 70 %     |
