# Water-Potability

I used water potability dataset (kaggle.com/code/dhruba60601/water-potability-drinking/data) to make a model for predict it's potability. This dataset contains some of organic,inorganic or compounds of water. Base of these the model is created according to i'ts necessity.

First I used all the algorithms of Machine Learning. At that time the result is not good. Also there are missing values. First scalling is done, because the range is not same for all the features. Then first KNN is used, then I got 66%. Then I also used Random forest. At that time I got accuracy 67%. Then I have used Boosting technique for model building(Gradient Boost and XGBoost), then I got 66%. 

So I come to know that these 3 algorithms gives us better result, if we used scalling. Otherwise we'll get the low accuracy.
For better results I tried to optimize our models by handling missing value using different techniques. But I got the same accuracy.
