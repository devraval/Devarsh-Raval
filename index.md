<img src="https://user-images.githubusercontent.com/66875776/114044770-1e1c3180-984d-11eb-8ced-7b5215a6a5f5.png" width="145" height="150">

# Devarsh Raval

Howdy, my name is Devarsh Raval and welcome to my project portfolio. I am a Master's student pursuing Industrial Engineering with a data science specialization. In the past year I have been learning data science through personal projects using datasets that pique my interest such as financial, demographics and consumer data. 

### Contact

LinkedIn : https://www.linkedin.com/in/devarsh-raval-1b8961188/

email : devarshraval@tamu.edu

phone : +1 9794225339

# Projects

## [Game Of Thrones Final Season Twitter Sentiment Analysis](https://github.com/devraval/GOT_S08_sentiments) 

The objective is to predict how a tweet would rate the tv series on scale of 10 compared to reviews on IMDb. For this, a custom model is to be built trained on the IMDb reviews and a pre-trained model vader sentiment also is to be used. It is an ongoing project. 

## [IPL data analysis in SQL](https://github.com/devraval/ipl-data-analysis)

The analysis was done using Postgresql database management system.

Key insights sought during analysis such as 

1)Team with most wins over entire time frame and per season

2)Common attributes of top run scorers such as age, batting style, experience :

(a) Top run scorers are 5 years older on average. (b) 40 % more likely to be left handed batsman than on average. (c) Has played 20-25 more matches than the average player.

3)Most valuable batsmen based on correlation of their runs and team victory.

<img src="https://user-images.githubusercontent.com/66875776/114050096-984eb500-9851-11eb-9be7-86edd4f83390.png" width="400" height="300">

4)Toss decision to win match, based on venues.

## [Predicting financial recessions based on macroeconomic indicators](https://github.com/devraval/Predicting-financial-recessions-based-on-macroeconomic-indicators)

For the macroeconomic indicator data, the most used website is The World Bank's followed by FRED(Federal Reserve Bank Of St.Louis). The website has categories to choose indicators from as decribed herein. The free API needs symbol of each indicator to collect data, the list of which is compiled here manually.
Stock market data is collected from yahoo finance and quandl.com as FRED api function in this notebook collects default option of daily stock market data.
Time frame is selected from 1996 to Aug 2020 according to available data. Consistent with the previous works in the literature, we use business cycle dating chronology provided by NBER which involves dates when recession began and ended in US economy. According to NBER's statistics we have 8 recession periods in our dataset where duration is changing from 6 to 18 months. We represent regimes as "Normal" and "Recession" in our dataset. 

<img src="https://user-images.githubusercontent.com/66875776/114125930-041a3780-98bd-11eb-93a9-6e45d3b26637.png" width="700" height="300">

Thus, the blue line graph past 2014 is the predicted probabilities of our model. One can see it does not predict recession for continuous two months until 2020 when the actual recession started. Limitation of this model is the period range of data selected is shorter. Thus, with more sophistication this model can be used to predict market recession in one month prior.


## [Telecom Customer churn prediction](https://github.com/devraval/Telecom-Customer-churn-prediction)

Customer churn is a critical metric because it is much more cost effective to retain existing customers than it is to acquire new customers as it saves cost of sales and marketing.In this dataset, it is defined as a binary variable for each customer and calculating the rate is not the objective. The concept of the churn rate indicates there are factors which influence it and thus the objective here is to identify and quantify those factors.

Several Machine Learning models were applied and one neural network model using Keras was applied.

#### Logistic Regression
Classification table and ROC AUC plot

<img src="https://user-images.githubusercontent.com/66875776/113955831-14111900-97e2-11eb-8c4f-91719fdae5a4.png" width="400" height="375">

#### Neural Network
A 64-8-1 dense layered model with a decaying learning rate of batch size 32 is used.

<img src="https://user-images.githubusercontent.com/66875776/113955096-b8925b80-97e0-11eb-9c11-bbb8c963be0c.png" width="400" height="300">
<img src="https://user-images.githubusercontent.com/66875776/113956004-6d794800-97e2-11eb-9b90-09d02c1e9d09.png" width="400" height="300">

Feature importance in the NN model

<img src="https://user-images.githubusercontent.com/66875776/113955593-ab29a100-97e1-11eb-8a1d-e8e974b35eab.png" width="400" height="300">


## [Investment portfolio analysis and optimization](https://github.com/devraval/Portfolio_Analysis_Optimization)

This is a portfolio analysis and comparison of Vanguard MidCap ETF(IVOO) to the index it tracks, S&P 400 MidCap (MID). The main contents are:

Factor analysis of MID and IVOO, namely for market beta, Value and Size.

Comparison of weighting techniques such as Global minimum variance (using different covariance estimation methods), equally weighted, and the Cap-weighted index that is listed on the market.

Style Analysis of Vanguard ETF using the 12 industry portfolio from FamaFrench website and in comparison to the entire index.

Comparison of performance of Vanguard ETF returns to various equity-bond portfolios.

