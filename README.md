# llSPS-INT-2347-Predicting-Life-Expectancy-using-Machine-Learning
## Predicting Life Expectancy using Machine Learning

### Data
Although there have been lot of studies undertaken in the past on factors affecting life expectancy considering demographic variables, 
income composition and mortality rates. It was found that affect of immunization and human development index was not taken into account in 
the past. Also, some of the past research was done considering multiple linear regression based on data set of one year for all the countries. 
Hence, this gives motivation to resolve both the factors stated previously by formulating a regression model based on mixed effects model and 
multiple linear regression while considering data from a period of 2000 to 2015 for all the countries. Important immunization like Hepatitis B,
Polio and Diphtheria will also be considered. In a nutshell, this study will focus on immunization factors, mortality factors, economic factors,
social factors and other health related factors as well. Since the observations this dataset are based on different countries, it will be 
easier for a country to determine the predicting factor which is contributing to lower value of life expectancy. This will help in suggesting 
a country which area should be given importance in order to efficiently improve the life expectancy of its population. 

Here is the data set- [Dataset](https://www.kaggle.com/kumarajarshi/life-expectancy-who)

### Code
Code is based on Python 3.7 and runs a basic linear regression on scikit learn, to give a RMSE of about 3.77
To run the code locally, simply download the .ipynb file and run the notebook on a Jupyter Notebook, preferably by downloading Anaconda Package

### Deployment
The deployment consists of a NODE RED flow in flows.json and links to a UI which can be found at this [link](https://node-red-xskfb.eu-gb.mybluemix.net/ui/#!/0?socketid=OrQbhOPGTo_993iMAAAA)
