Problem definition
The number of financial transactions is fluctuated during the day based on different parameters in the market. "Time" and "ERU to USD rate" are two parameters that could influence the number of transactions.
The attached three-days dataset records the rate of EUR to USD in each minute and also the number of financial transactions (column G in the data set).
You are asked to provide an appropriate model to predict the number of financial transactions during a day based on recorded parameters.

More information about the dataset
1. Each row shows the data, which is recorded for one minute window.

2. Each row captures the rate of EUR to USD (E/U) in 4 snapshots, including:

Open: The rate of E/U when the 1-minute window is opened.
Close: The rate of E/U when the 1-minute window is closed.
High: The highest value for E/U rate during the 1-minute window.
Low: The lowest value for E/U during the 1-minute window.



Results:
Predicted the number of financial transactions using Linear Regression with R-Squared value of 0.5643