# WomenE-CommerceSentimentAnalysis  
Sentiment Analysis of Women's E-commerce clothing data  
## Project Milestones:
1) Describe the data  
    a) Descriptive statistics, data type, etc.  
2) Analyze the text comment/ review and share the findings  
3) Convert the ratings into 2 classes  
    a) Class: Bad when Rating <=3  
    b) Class: Good otherwise  
4) Develop a model to predict the Rating class (created above)  
    a) Focus on steps to build a model  
    b) Which algorithm can be used and why  
5) Share the findings of the model.  

### Data Analysis  
![](https://github.com/dipanshug124/WomenE-CommerceSentimentAnalysis/blob/master/images/AgeDistribution.png)
![](https://github.com/dipanshug124/WomenE-CommerceSentimentAnalysis/blob/master/images/AgeDistributionByClass.png)
![](https://github.com/dipanshug124/WomenE-CommerceSentimentAnalysis/blob/master/images/AgeDistributionVSAge.png)
![](https://github.com/dipanshug124/WomenE-CommerceSentimentAnalysis/blob/master/images/CategoryVsAGE.png)
![](https://github.com/dipanshug124/WomenE-CommerceSentimentAnalysis/blob/master/images/CountCategory.png)
![](https://github.com/dipanshug124/WomenE-CommerceSentimentAnalysis/blob/master/images/CountVSAge.png)
![](https://github.com/dipanshug124/WomenE-CommerceSentimentAnalysis/blob/master/images/Polarity.png)
![](https://github.com/dipanshug124/WomenE-CommerceSentimentAnalysis/blob/master/images/reviewLengthVSrating.png)
![](https://github.com/dipanshug124/WomenE-CommerceSentimentAnalysis/blob/master/images/RatingCount.png)
![](https://github.com/dipanshug124/WomenE-CommerceSentimentAnalysis/blob/master/images/allWords.png)
![](https://github.com/dipanshug124/WomenE-CommerceSentimentAnalysis/blob/master/images/negativeWords.png)
![](https://github.com/dipanshug124/WomenE-CommerceSentimentAnalysis/blob/master/images/positiveWords.png)

**Downloading data** 
Added it here as [Womens_Clothing_E_Commerce_Reviews.csv](https://github.com/dipanshug124/WomenE-CommerceSentimentAnalysis/blob/master/Womens_Clothing_E_Commerce_Reviews.csv))  

**Libraries**
* `Numpy` :http://www.numpy.org/
* `Pandas` :http://pandas.pydata.org
* `matplotlib` :http://matplotlib.org/
* `seaborn` :https://seaborn.pydata.org
* `Datetime` :https://docs.python.org/3/library/datetime.html
*  `Statistics` :https://docs.python.org/3/library/statistics.html

**Software Recommended**
* [Jupyter Notebook](http://ipython.org/notebook.html)
* [Anaconda](http://continuum.io/downloads) installed with `Python 3.8`  


### Model Output  
From Notebook_1 we get the following inferences:  
1. Logistic Regression : 93.04%  
2. KNeighborsClassifier : 92.45%  
3. DecisionTreeClassifier: 91.23%  
4. Naive Bayes : 89.58%  
lOGISTIC REGRESSION works best for our data set followed by KNeighborsClassifier.  

From Notebook_2 we get the following inferences:  
Model with SVM using hyperparameters tuning we get the efficiency upto 93.43%.
