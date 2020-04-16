# Machine-Learning-series---Linear-Regression
In the Series of Machine learning will share the Linear regression 

sklearn.model_selection is the library 
train_test_split

1.Error 	: 
SyntaxError: invalid syntax

1.CodeSnippet:
from sklearn.linear_model import LinearRegression()

1.Root cause : 
LinearRegression() is not correct rather it shoud be LinearRegression

2.

Error:
ValueError: Expected 2D array, got 1D array instead:

CodeSnippet:
 regressoragent.fit(X_Train,Y_Train)

Fix: We need to reshape the data.use column.values.reshape() and also assign it back to 

Common Mistake  : X.values.reshape(-1,1) and not asigning back will retain the same shape.

to correct, do X=X.values.reshape(-1,1)

Fit and Predict requires 2-D array rather than 1 D array.
