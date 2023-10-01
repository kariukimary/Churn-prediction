# Churn-prediction

imagine you're working with Sprint, one of the biggest telecom companies in the USA. They're really keen on figuring out how many customers might decide to leave them in the coming months. Luckily, they've got a bunch of past data about when customers have left before, as well as info about who these customers are, what they've bought, and other things like that.
   So, if you were in charge of predicting customer churn, how would you go about using machine learning to make a good guess about which customers might leave? What steps would you take to create a machine learning model that can predict if someone's going to leave or not? 

   
LOADING THE DATASET AND IMPORTING NECESSARY LIBRARIES

I used panda’s library to load the dataset downloaded from Kaggle, I also imported other required libraries to be used in creating the model.


DATA EXPLORATION AND ANALYSIS

	I did some analysis of the data by getting the shape of the data, 

	getting the columns names since there we so many to fit the entire width,

	getting the unique items for various columns such as target variable among others, 

	checking for empty values and duplicates in the dataset. The dataset had no duplicates and null values thus the data cleaning part was not necessary at this point.

	getting the statistical summary of the data which helped me in making the decision of not scaling the data.


DATA VISUALIZATION 

This involved graphical representation of the data so as to get patterns and insight from the data. I visualize various features such as age, tenure, monthly charges and also the target variable.


DATA PREPROCESING

This involved feature selection where I dropped the unnecessary columns also, I did some feature transformation where I encoded the categorical variables to numerical values.


BUILDING THE MODEL AND EVALUATION

I used RandomForestClassifierin building the model, in evaluation I used accuracy score and confusion matrix to evaluate the performance of the model
