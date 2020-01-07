
Dataset:
The data we use is the famous HELOC data from Fico.
You can find the dataset as HelocData.csv in this repo.

Feature Engineering:
Nealy raw data as input. We merely impute missing values without further feature engineering.
Because it turns out to be the optimal option for the data and model.

Model:
With Gredient Boosting, we reached an overwhelming accuracy rate on the test dataset at 0.7742 (very minimum feature engineering).

Hyperparameter Tuning:
We used RandomizedSearchCV to generate the hyperparameter space and cross validation to get the best hyperparam.

Interpretability:
We use post-hoc and SHAP value only to interpret our model. Because SHAP value is additive. 

Let me know if you have any questions.

PS.
As I know of, Duke and NYU folks only managed to reach an accuracy score of ~75%.
