Documentation Link: https://azista.atlassian.net/wiki/x/BoBbFg

**Main Concept: Lag Features**

What are Lag Features?
Lag features are used in time series data to capture the relationship between past and current values of a variable. These features are created by "shifting" the time series data, meaning that you use previous time steps as input for predicting the current or future values. In simple terms, a lag feature represents the value of a time series at an earlier time point.

For example: If you are predicting the value of a time series at time t, a lag-1 feature will use the value from time t-1, a lag-2 feature will use the value from time t-2, and so on. By incorporating lag features, you help the model learn from the past behavior of the series.

Example of Lag Features
Let’s consider a simple time series where we are trying to predict the daily sales for a store based on past sales data. Here's a sample dataset:

![image](https://github.com/user-attachments/assets/6a913ce5-13f8-4d0f-a030-fe350893e1fa)

If we want to predict the sales on Day 5 based on previous days' sales, we can create lag features. For instance:

Lag-1 (Sales on the previous day): This feature will contain the sales from the previous day.
Lag-2 (Sales two days ago): This feature will contain the sales from two days ago.
Here’s how the lag features would look:

![image](https://github.com/user-attachments/assets/3d4b97a0-e669-4a66-a7ab-2b0ee893ae87)

Lag-1 Sales for Day 5: This is the sales value from Day 4, i.e., 230.
Lag-2 Sales for Day 5: This is the sales value from Day 3, i.e., 215.
