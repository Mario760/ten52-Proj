# ten52-Proj

There are two types of files are included in the project: Data and ML models.

The Data includes the stock data from 5 companies as mentioned before. The date is from 2022-02-24 to 2023-02-23. We used all data except the last month's data as the training data and the last month's data (in Feb,2023) as the test data.

All data files are stored in the Data folder. The ML models are stored in the root folder. The seed files such as detrendPrice.py, WhiteRealityCheck.py that from lectures are also stored in the root folder. Besides, the root folder also contains our presentation slides.

Moreover, the White Reality Check generate the result file of dfP_Simple.csv stored in the Results folder.



In the project, we use the stock data from Apple, Amazon, Google, META, and Netflix to predict the Apple stocks.

All data are downloaded from Yahoo Finance from https://finance.yahoo.com/lookup.

We applied several machine learning models: Linear Regression (with and without PCA), Random Forest, Decision Tree, KNN to predict the Apple stocks. In the Linear Regression with PCA model, we also used the Amazon, Google, META, and Netflix to assist predicting the trend of Apple stock.



To run each model:
    1. download from GitHub Repo
    2. extract the zip file (if cloned, skip this step)
    3. open each ipynb file by using jupyter notebook
    4. directly run the code.
