# Portfolio Optimization

The following repository will focus on the global minimum variance to decide of the optimal portfolio and we will use penalty regularization on training data to build robust estimations of the assets' weights. The dataset used comes from Ken French’s website (http://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html) and contains daily equity returns for 48 industries in the U.S. from 1926 onwards. 

- First, we are using the whole dataset, that is to say daily returns of 40 industries (we took out soda, rubber, health, FabPr (Fabric Products), guns, gold, PerSv (personal service), and paper as it had missing values)

- Second, we are using values since 2001-2007 to train the dataset and the 2007-2008 financial crisis as testing dataset. We chose this interval to look at how a portfolio made before a financial crisis would work during the financial crisis
