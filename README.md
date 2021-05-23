# Linear-Regression
Linear Regression from Scratch.
Linear Regression is a method used to define a relationship between a dependent variable (Y) and independent variable (X). Which is simply written as:
**y=m*x+b**
Where y is the dependent variable, m is the scale factor or coefficient, b being the bias coefficient and X being the independent variable. The bias coefficient gives an extra degree of freedom to this model. The goal is to draw the line of best fit between X and Y which estimates the relationship between X and Y.
But how do we find these coefficients, we can find these using different approaches. One is the Ordinary Least Mean Square Method approach and the Gradient Descent approach. We will be implementing the Gradient Descent approach.
 This is called the analytical method of solving the equation. Nothing wrong in this however remember machine learning is about programming in matrices. For sake of machine learning I can express the equation for a line in terms of machine learning in a different way. I would call y as my hypothesis and represent it as J(theta) and call b as theta0 and m as theta1. I can write same equation as 
Looks simple but mathematically how can we represent this. Here is the maths:

## RESULTS:
Results obtained using all the algorithms above mentioneed.
We can divide our data in test and train sets for checking our algorithms efficiency. After dividing we train our algo on train data. Here below is the graph of training data which spreads in graph.

![GitHub Logo](/images/TestDataSet.png)

After that we test our data on algorithm and make a best fit line which are shown below in the graph. Here cross point which are shown on the graph are training data and other points are testing data. Here is the green line is the best fit line which divide our data into two pieces. 

![GitHub Logo](/images/Fit.png)

After that we make a graph which clearly shows the error of each point from the best fit line. We use a plotly graph for achieving the error graph. First, we make a graph and after that we append the line between the point and best fit line. For this we calculate the distance between the point and the line. 

![GitHub Logo](/images/ErrorLine.png)

Here we make a graph which shows the relation between the cost and iteration. For making our algorithm best we use the iteration factor. In this graph we clearly see that if the number of iterations increase cost decreases and after some time its constant and does not any changes see. So, for making our algorithm best we find this state.

![GitHub Logo](/images/costFun.png)
