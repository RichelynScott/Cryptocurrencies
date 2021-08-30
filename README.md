# Mod 18 –Machine Learning: Supervised & Unsupervised Learning– Cryptocurrencies
### Overview of Analysis 

This analysis uses supervised and unsupervised learning with Cluster Algorithms and K-Means algorithms to create an analysis for clients who are preparing to get into the cryptocurrency market.

### Results

Pandas and scikit-learn libraries were used to prepare the data for Principal Component Analysis to reduce the number of dimensions upon which to cluster the cryptocurrencies.
The K-Means clustering algorithm in scikit-learn was used to assign classes to each cryptocurrency and then plotly and HVplot were used to visualize cluster results as well as an elbow curve to help identify the number of groups to cluster the cryptocurrencies. For this analysis the K-Means algorithm was run with k=4. Screenshots below of the elbow curve & HV Plot table.
![Elbow Curve](https://github.com/RichelynScott/Cryptocurrencies/blob/main/Elbow%20Curve.png)

![HV Plot](https://github.com/RichelynScott/Cryptocurrencies/blob/main/D4%20HV%20Plot.png)

Once each cryptocurrency was assigned to a class, the clusters were plotted on a 3-D interactive scatter plot.  The chart can be manipulated by rotation on x & y axis and information about each cryptocurrency appears when hovering over their data point.
![3D Scatter](https://github.com/RichelynScott/Cryptocurrencies/blob/main/3D%20Scatter%20Plot.png)
