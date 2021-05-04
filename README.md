# Client-Sales-Projections-and-Bucketing
Projected the spending patterns of clients 12 months into the future, and then bucketed them into high, medium, and low priorites for advertising.

- Used dual Autoregressive Integrated Moving Average (ARIMA) models to simultaneously project rolling 12 month sales and rolling 12 month redemptions.
- Took the net change between these outputs as the final projection for a clients spending 12 months into the future.
- Bucketed clients with one dimensional KMeans clustering after temporarily removing outliers as to not create poor clustering centroids.

![alt text](https://github.com/MadMattF/Client-Sales-Projections-and-Bucketing/blob/main/Projections%20Visual%20Example.PNG?raw=true)
