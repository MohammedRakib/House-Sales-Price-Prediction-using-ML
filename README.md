For this project, I extensively use plotly, seaborn and matplotlib for data visualization and ML Algorithms to predict house prices in Ames. This is a regression problem.

 **Goal** <br>
Predict the sales price for each house. For each Id in the test set, I must predict the value of the SalePrice variable. 

 **Metric** <br>
Submissions are evaluated on **Root-Mean-Squared-Error (RMSE)** between the **logarithm** of the predicted value and the **logarithm** of the observed sales price. (Taking logs means that errors in predicting expensive houses and cheap houses will affect the result equally.)
