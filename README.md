# module-14
algo-trading fintech homework

Parameter Tuning

I think that having a 3 month training data was the best because it maximized the positive margins between the strategy strategy and the actual returns the most at every point in time. Decreasing or increasing the training data length seemed to have negative impact as seen in the following graphs below. In terms of the most ideal SMAs. I found that the ideal parameter for the short window was 3 and the ideal for the long window was 110. I think that increasing the short window too much or decreasing it by too much made the two strategies converge and there was no margin between the actual returns and the trading strategy. 

This is the baseline parameters graph. 
![alt text](https://github.com/jtrieu2/module-14/blob/main/baseline.png)

Below is the image for 3 months training data, short window of 3 and long window of 110. 
![alt text](https://github.com/jtrieu2/module-14/blob/main/ideal_params_short_3_long_110.png)

The following images below are iterations on the length of the training data.

1 month
![alt text](https://github.com/jtrieu2/module-14/blob/main/1month.png)

3 month
![alt text](https://github.com/jtrieu2/module-14/blob/main/3month.png)

6 month
![alt text](https://github.com/jtrieu2/module-14/blob/main/6month.png)

Evaluation Report of Classifiers
I think that the logistic regression model outperformed the svm model based on the following graphs. Both of them had the same parameters and same testing/training set.

