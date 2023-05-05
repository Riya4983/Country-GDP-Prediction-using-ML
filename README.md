
<img width="967" alt="Screenshot 2023-05-05 at 2 40 35 PM" src="https://user-images.githubusercontent.com/129305827/236419968-e1013dcf-0460-4951-b673-4c30554d73f9.png">

GDP prediction of Countries

DATA SOURCE: 'Countries of The World' data set (from kaggle: Fernando Lasso: https://www.kaggle.com/fernandol/countries-of-the-world).

DATA DESCRIPTION: We have 227 countries and 20 columns for each country. Each column represents some aspect that influences the corresponding country's GDP. 

OBJECTIVE: To predict the GDP per capita of the countries and identify some major trends.

FINAL FINDINGS: 4 different learning regressors (Linear Regression, SVM, Random Forest, and Gradient Boosting) were tested, and we have achieved the best prediction performance using Random Forest, followed by Gradient Boosting, then Linear Regression, while SVM achieved the worst performance of the four.

Best results of Random Forest regression :
- Mean Absolute Error (MAE): 2142.13
- Root mean squared error (RMSE): 3097.19
- R-squared Score (R2_Score): 0.8839
![RF prediction](https://user-images.githubusercontent.com/129305827/236416421-02b486e1-4f81-4df7-bdee-ff287429abd9.png)

