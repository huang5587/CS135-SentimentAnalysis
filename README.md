# Sentiment Analysis on Online Customer Reviews

This repositry contains the data and code for a sentiment analysis conducted on online customer reivews. I trained 3 models (Logistic Regression, Neural Network and SVM). Of the three, the logisitic regression model performed the best with an accuracy score of ~85%

## Process

In order to increase data reliability, I implemeneted the common pre-processing steps of tokenization, removal of punctuation and stop words, converting to lowercase and stemming. 

Before training my models I used a five-fold cross validation via ntlk's GridSearchCV. GridSearchCV also helped to identify the optimal parameters and their optimal values. 

## Improvements

If I were to repeat this process again, I would consider using a larger data set. In addition, in order to save time I kept some of the parameter ranges quite limited. If I had more computing resources and time available, I would certainly expand the parameter ranges and create more models to more deeply investigate the effectiveness of each type of model. 
