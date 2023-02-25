# Bank-Customer-Churn-Data-Analysis

#### The objective of this project is to build a predictive model that can predict customer churn for a given company and use machine learning techniques to build the model and document the process, including feature selection, model evaluation, and performance metrics.

[Dataset link](https://www.kaggle.com/competitions/bank-marketing-uci/overview)

### bank client data:
   1 - age (numeric)</br>
   2 - job : type of job (categorical: "admin.","unknown","unemployed","management","housemaid","entrepreneur","student","blue-collar","self-employed","retired","technician","services")</br>                                       
   3 - marital : marital status (categorical: "married","divorced","single"; note: "divorced" means divorced or widowed)</br></br>
   4 - education (categorical: "unknown","secondary","primary","tertiary")</br>
   5 - default: has credit in default? (binary: "yes","no")</br>
   6 - balance: average yearly balance, in euros (nume</br>
   7 - housing: has housing loan? (binary: "yes","no")</br>
   8 - loan: has personal loan? (binary: "yes","no")</br>
### related with the last contact of the current campaign:</br>
   9 - contact: contact communication type (categorical: "unknown","telephone","cellular") </br>
  10 - day: last contact day of the month (numeric)
  11 - month: last contact month of year (categorical: "jan", "feb", "mar", ..., "nov", "dec")</br>
  12 - duration: last contact duration, in seconds (numeric)</br>
### other attributes:
  13 - campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)</br>
  14 - pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means client was not previously contacted)</br>
  15 - previous: number of contacts performed before this campaign and for this client (numeric)</br>
  16 - poutcome: outcome of the previous marketing campaign (categorical: "unknown","other","failure","success")</br>
### Output variable (desired target):
  17 - y - has the client subscribed a term deposit? (binary: "yes","no")</br>
  
### Conclusion:
Built a predictive model using different Machine Learning techniques to predict bank customer churn for the bank.</br>
Used Decision Tree, Linear Regression, Random Forest, Gradient Boosting and Naive Bayes.</br>
Using Evaluation metrics and AUR-ROC curve graphs found that among all above models the Gradient Boosting model is best predictive model in this case.</br>
AUC - ROC curve is a performance measurement for classification problem at various thresholds settings. </br>
ROC is a probability curve and AUC represents degree or measure of separability. </br>
It tells how much model is capable of distinguishing between classes. </br>
Higher the AUC, better the model is at predicting. </br>
Hence from the above graph Gradient Boosting model is the best.</br>
