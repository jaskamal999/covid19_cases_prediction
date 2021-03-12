# covid19_cases_prediction
Python project of predicting future Covid19 cases, deaths and recoveries using fbprophet.

The dataset used in this project is taken from kaggle: https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset
This had dataset of Covid19 cases until 6 Dec 2020.
Using this data, a model was trained to predict the future case, deaths, and recovery count based the trend observed in the dataset. Fbprophet was used to do this traning.

**Results:**

As of 12 March 2021, which is more than 3 months to the last date of dataset, our model's predictions and actual numbers are as follows:

Actual confirmed cases on 12 March 2021 - 119M
Confirmed cases predicted by 12 March 2021 - 113.4M
![screenshot1](https://user-images.githubusercontent.com/47657501/110932304-2762be80-82e0-11eb-9642-66a84c4ff08d.JPG)

Actual deaths on 12 March 2021 - 2.63M
Deaths predicted by 12 March 2021 - 2.22M
![screenshot2](https://user-images.githubusercontent.com/47657501/110932567-86c0ce80-82e0-11eb-9f49-376243a45ac6.JPG)

Actual recovered cases on 12 March 2021 - 67.1M
Recovered cases predicted by 12 March 2021 - 68.3M
![screenshot3](https://user-images.githubusercontent.com/47657501/110932779-c7b8e300-82e0-11eb-8791-9dfc46ed972e.JPG)

Here is an example of the trend observed in confirmed cases along with the daily analysis of which days of the week saw how many cases
![screenshot4](https://user-images.githubusercontent.com/47657501/110933327-75c48d00-82e1-11eb-872d-e6b284eaf799.JPG)


