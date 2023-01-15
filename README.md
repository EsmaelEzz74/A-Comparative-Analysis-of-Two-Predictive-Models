# A-Comparative-Analysis-of-Two-Predictive-Models
Unlocking the Secrets of Diabetes through Machine Learning Techniques
- Reading and examining the data set found that all column types are either float or integer. This will make things easier for us, and when I checked for zeros, it looks like there are a bunch of zeros in five columns out of eight, so I filled those zeros with the mean of each column due to data lack
- When drawing the seaborn heatmap to show the correlated features in the data, it turns out that we will be using all the data columns
- <img src = "https://user-images.githubusercontent.com/85246622/207991503-42808772-ce41-4ba9-a6d4-0fa921b2d40c.png" width = "400" height = "400" />
---------------------------------------------
- And for more data visualization here is the seaborn pairplot 
- <img src = "https://user-images.githubusercontent.com/85246622/207991666-7df08fbb-1940-4180-aee5-3e5f79d4adc6.png" width = "1000" height = "800" />
---------------------------------------------
- Arriving at the Sklearn model, I split the data into test and training sets with a ratio of 0.2 to 0.8 and use MinMaxScaler to perform data normalization and fit the data to the model to get the test set to predict and get a score
---------------------------------------------
- Then the coding of my logistic regression function includes several stages, first the data split, second the sigmoid function to calculate the formula, then the calculation of the cost function using its coded function, finally the prediction function to predict the test set, and then print out the score that there is almost no difference between the two models
