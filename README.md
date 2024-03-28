# PhoneBank
This project was conducted to understand the probability that a phone call is answered and the variables involved. Which factors enhance the probability that someone answers a call? Which factors decrease that probability?

Several variables were recorded: caller, date, time, area code used to call, school department, calls attempted, and calls answered. Data was collected from December 2020 to May 2021.

Click PhoneBankAnalysis.ipynb to view the analysis.

First, the data was imported and a bar chart was created to find the percentage of all calls answered (22%). Next, bar charts were created to understand how the day of the week and time of day affect pick-up rate. Area code and department were also investigated. Various t-tests were performed to test if pick-up rate is higher given certain variables. Lastly, a logistic regression model was trained to predict the probability of a call being answered. Time of day and day of the week appear to be important factors, with the 11 AM time slot being negatively correlated with call pick-up and Wednesdays being positively correlated with call pick-up. Below is a screenshot from the python notebook.

<img src="https://i.ibb.co/kqKVYKS/pickup-rate.png" width="350">

Feel free to add to our dataset [here](https://docs.google.com/spreadsheets/d/1puDThi9dyA1APUbSW2i5xbk2cJi7lvI_Xzo4pzyB_qw/edit?usp=sharing).
