# machine-learning-concepts
Machine learning forms the core understanding for data mining , data warehousing , deep learning , artificial intelligence and many more. Machine learning is closely related to computational statistics, which also focuses on prediction-making through the use of computers. It has strong ties to mathematical optimization.Most features of data analytics are mahcine learning derivative.It is used to train computer systems to extract decision out of he data.It gives the computer systems power to make decisions , learn from evironment through basic algorithms . Acquiring Machine Learning concepts with supporting programs is very essential.Tech giants extensively use machine learning to power up different predictable trsnsactions.

I used machine learning to build decision models in a small scale.Some of the basic concepts sorrounding the topics such as linear regression , classification , decision trees  and clustering has been shown here.

1.Linear regression 
Machine learning, or any predictive modeling structure is primarily concerned with minimizing the error of a model or making the most accurate predictions possible based on rpovided data, at the expense of explainability. In applied machine learning we will borrow, algorithms from many different fields, including statistics and use them towards simplifying our goals .

As such, linear regression was developed in the field of statistics and is studied as a model for understanding the relationship between input and output numerical variables. It is statistical algorithm and maps to machine learning concepts in which we make decisions like predicting the
              1.Amount of rain for a day given the Rainfall data for past 2 months.
              2.Stock Price for product with given stock data.
              3.Performance of students in academics or any other discipline with a given set of result data.
As all the above examples show us that Linear regression is built on the given dataset which gives an output for our model.It presents decision quantitaively.
The Simple Linear Regression model can be reprsented as Y=C+AX1+BX2
The implementation of Simple Regression model is shown in Untitle3.py code using data set is LR_X.txt and LR_Y.txt.

2.Logistic Regression
Logistic Regression is based on the concept of Regression over the logistic function.Also called the sigmoid function It’s an S-shaped curve that can take any real-valued number and map it into a value between 0 and 1, but never exactly at those limits.
                                                   1 / (1 + e^-value)
 Logistic regression predict probabilities which can be written as P(sex=male|height).Note that the probability prediction must be transformed into a binary values (0 or 1) in order to actually make a probability prediction. More on this later when we talk about making predictions.The regression is linear model but gets transformed using function. 
                                             p(X) = e^(b0 + b1*X) / (1 + e^(b0 + b1*X))
The best prediction will make an estimation close to 1.The maximum-liklihood for the logistic regression will be a search for values for best coefficients.The data used for logistic regression must be noise free .
An example for simple logistic regression model has been shown in LogisticRegression.py and data sets for this model is given with irisx.csv and irisy.csv
