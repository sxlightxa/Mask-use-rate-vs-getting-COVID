# Mask-use-rate-vs-getting-COVID
Used: linear regression(OLS), Pandas, numpy, matplotlib.
Done on Python 3 on Dec 2021.

I was interested in how does mask-use rate impact the chance of getting COVID with a consideration of population density of each states.
Download ipynb to view or view html file: 

I.
Download COVID cummulative confirmed cases for each states raw data from:  https://github.com/nytimes/covid-19-data/tree/bde13b021e99c6b4a63fb66a6144e889cc635e31.
Donwloaded estimated mask-use rate at county level from a survey done by NY times and Dynata in July 2020.

II.
Cleaned and scaled 2 large datasets, combined dataframes, filtered releavant data (May, June, July 2020), and created new variables mask-use score.

III.
Ran different exploratory analysis on mask-use score and COVID increase rate. Found for more populated states (>= 75% percentile), more mask-use rate significantly reduced the chance of getting COVID.


