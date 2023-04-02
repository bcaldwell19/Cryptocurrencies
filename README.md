# Cryptocurrencies
## Background
>Martha is a senior manager for the Advisory Services Team at Accountability Accounting, one of your most important clients. Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. So, they’ve asked you to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

>The data Martha will be working with is not ideal, so it will need to be processed to fit the machine learning models. Since there is no known output for what Martha is looking for, she has decided to use unsupervised learning. To group the cryptocurrencies, Martha decided on a clustering algorithm. She’ll use data visualizations to share her findings with the board.

**Programming Language**: Python 

**Libraries**: PANDAS,hvplot,SKlearn,pathlib,plotly

**Method**: Principal Component Analysis (PCA) 

**Clustering Model**: K-means
____________________________________________________________________________

## Summary 

This is a introductory project to unsupervised machine learning.  In this project, we use a clustering algorithm on a cryptocurrencies dataset. Our goal is to understand the relationship between our data features and the independent variable, and share the results with Accountability Accounting's board about possible investment opportunity.  The independent variable in this project is class. Another way to interpret class would the grouping to which it belongs to with respect to the other data points. 

### Analysis 

The cryptocurrency dataset can be split into four separate classes.  This was estimated using an elbow curve. A combination of PCA and K-means model helped us partition the data into 4 clusters.

Martha can share the two separate visualizations with the board.  The first figure would be a 2D representation of the post-processed dataset.  The second figure is a 3D representation of the post-processed dataset. Martha needs to use both figures to describe what was observed by our model.  Only using one figure would only tell part of the story. 


![2D Scatter](/images/2D_scatter.png)

**Figure 1**: 2D Scatter Plot

![3D Scatter](/images/3D_scatter.png)

**Figure 2**: 3D Scatter Plot
