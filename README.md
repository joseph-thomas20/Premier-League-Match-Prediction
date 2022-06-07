# Premier-League-Match-Prediction
Using online data on Premier League matches scraped using python and Beautiful Soup, here I develop a Random Forest Model to predict the outcome of Premier League Matches

Project Steps:
- I scraped match data from the 2020-2021 and 2021-2022 seasons from FBref's website using requests, BeautifulSoup, and pandas.
- I then cleaned the data and prepared it to be ready for machine learning using pandas.
- I then developed an initial Random Forest Model using Scikit-Learn and measured the error
- The model was improved by adding predictor variables, implementing rolling averages and combining both home and away results over the two seasons

The final model had an accuracy of 65.11%.
The nature of sports, especially football make predicting the outcome of matches difficult, so I was pleased with this precision

A few ideas to improve the precision:
- Scraping data to use more seasons would help improve the accuracy of the predictions
- Using more predictors could also have an effect on the precision - such as managers, referees, additional matches outside the league, potentially a metric for home atmosphere
- Other models could be used, for example Neural Networks
