# CryptoClustering

For this challenge, I used my knowledge of Python and unsupervised learning to best predict if cryptocurrencies are affected by 24-hour or 7-day price changes. After I loaded the crypto_market_data.csv into a DataFrame.
I Got the summary statistics and used methods to plot the data to see what the data looks like before moving to the next step. I prepared the data, used the StandardScaler() module from scikit-learn to normalize the data from the CSV file, and created a DataFrame with the scaled data while setting the "coin_id" index from the original DataFrame as the index for the new DataFrame.

I then found the Best Value for k Using the Original Scaled DataFrame. I clustered cryptocurrencies with K-means Using the original scaled data and optimized clusters with principal component analysis.

Using the PCA Data was the best way to find the Best Value for k so I could then cluster cryptocurrencies with K-means using the PCA Data.
