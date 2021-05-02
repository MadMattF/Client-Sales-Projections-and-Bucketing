# Client-Sales-Projections-and-Bucketing
Was tasked with projecting the spending patterns of clients 12 months into the future, and then to bucket them into high, medium, and low priorites for advertising.

- Used dual Autoregressive Integrated Moving Average (ARIMA) models to simultaneously project rolling 12 month sales and rolling 12 month redemptions.
- Took the net change between these outputs as the final projection for a clients spending 12 months into the future.
- For client bucketing, one dimensional KMeans clustering was used after temporarily removing outliers as to not create poor clustering centroids.

![alt text](https://github.com/MadMattF/Client-Sales-Projections-and-Bucketing/blob/main/Projections%20Visual%20Example.PNG?raw=true)
