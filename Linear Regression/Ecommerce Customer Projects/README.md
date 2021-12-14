𝐋𝐢𝐧𝐞𝐚𝐫 𝐑𝐞𝐠𝐫𝐞𝐬𝐬𝐢𝐨𝐧 is a machine learning algorithm based on supervised learning. It performs a regression task. 
Regression models a target prediction value based on independent variables. It is mostly used for finding out
the relationship between variables and forecasting. Different regression models differ based on – the kind of
relationship between dependent and independent variables, they are considering and the number of independent 
variables being used.


![linear-regression-in-machine-learning](https://user-images.githubusercontent.com/85125898/146007554-f0ec7016-669a-4d64-a0f3-0c4c49e44ff2.png)



𝐇𝐲𝐩𝐨𝐭𝐡𝐞𝐬𝐢𝐬 𝐟𝐮𝐧𝐜𝐭𝐢𝐨𝐧 𝐟𝐨𝐫 𝐋𝐢𝐧𝐞𝐚𝐫 𝐑𝐞𝐠𝐫𝐞𝐬𝐬𝐢𝐨𝐧 :

![linear-regression-hypothesis](https://user-images.githubusercontent.com/85125898/146007532-5a81455f-543d-4a4c-8860-745587daeacd.jpg)


𝐖𝐡𝐢𝐥𝐞 𝐭𝐫𝐚𝐢𝐧𝐢𝐧𝐠 𝐭𝐡𝐞 𝐦𝐨𝐝𝐞𝐥 𝐰𝐞 𝐚𝐫𝐞 𝐠𝐢𝐯𝐞𝐧 :
x: input training data (univariate – one input variable(parameter))

y: labels to data (supervised learning)

𝐖𝐡𝐞𝐧 𝐭𝐫𝐚𝐢𝐧𝐢𝐧𝐠 𝐭𝐡𝐞 𝐦𝐨𝐝𝐞𝐥 – it fits the best line to predict the value of y for a given value of x.
The model gets the best regression fit line by finding the best θ1 and θ2 values.

θ1: intercept

θ2: coefficient of x

Once we find the best θ1 and θ2 values, we get the best fit line. So when we are finally using our 
model for prediction, it will predict the value of y for the input value of x.

How to update θ1 and θ2 values to get the best fit line ?

𝐂𝐨𝐬𝐭 𝐅𝐮𝐧𝐜𝐭𝐢𝐨𝐧 (𝐉):
By achieving the best-fit regression line, the model aims to predict y value such that the error
difference between predicted value and true value is minimum. So, it is very important to update 
the θ1 and θ2 values, to reach the best value that minimize the error between predicted y value
(pred) and true y value (y).

![LR-cost-function-1](https://user-images.githubusercontent.com/85125898/146008082-5589db28-3696-4048-882a-faba29062e0c.jpg)

![LR-cost-function-2](https://user-images.githubusercontent.com/85125898/146008091-9afcd4ae-4dfb-41c2-98df-f2acfc22da61.jpg)

Cost function(J) of Linear Regression is the Root Mean Squared Error (RMSE) between predicted y value (pred) and true y value (y).
