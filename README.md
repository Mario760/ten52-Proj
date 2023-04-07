# ten52-Proj

<b>Team Members:</b>
<ul>
<li>Jiawei Ma</li>
<li>Long Ye</li>
<li>Jingting Chen</li>
<li>Zhaoxi Liu</li>
</ul>

<br>
<b> Project Purpose:</b><br><br>
This project is to predict the APPLE Inc. stock Open price based on the data from 2022-02-24 to 2023-02-23.

<br><br>

<b> File Types:</b><br><br>
There are two types of files are included in the project: Data and ML models.

The Data includes the stock data from 5 companies as mentioned before. The date is from 2022-02-24 to 2023-02-23. We used all data except the last month's data as the training data and the last month's data (in Feb,2023) as the test data.

All data files are stored in the Data folder. The ML models are stored in the root folder. The seed files such as detrendPrice.py, WhiteRealityCheck.py that from lectures are also stored in the root folder. Besides, the root folder also contains our presentation slides.

Moreover, the White Reality Check generate the result file of dfP_Simple.csv stored in the Results folder.

<br><br>

<b> Data Sources: </b><br><br>
In the project, we use the stock data from Apple, Amazon, Google, META, and Netflix to predict the Apple stocks.

All data are downloaded from Yahoo Finance from https://finance.yahoo.com/lookup.

<br><br>

<b> Machine Learning Model Choice: </b><br><br>
We applied several machine learning models to predict the Apple stocks.: 
<ol>
<li>Linear Regression (with and without PCA)</li>
<li>Random Forest</li>
<li>Decision Tree</li> 
<li>KNN</li>
</ol> 

In the Linear Regression with PCA model, we also used the Amazon, Google, META, and Netflix to assist predicting the trend of Apple stock.

<br><br>

<b>To run each model:</b>
<ol>
    <li>download from GitHub Repo</li>
    <li>extract the zip file (if cloned, skip this step)</li>
    <li>open each ipynb file by using jupyter notebook</li>
    <li>directly run the code.</li>
</ol>

<b>Thanks to Professors Sabatino Costanzo-Alvarez and Rosario Lorenza Trigo-Ferre for their teaching and guidance this semester</b>
