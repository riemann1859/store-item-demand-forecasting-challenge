In this project we are given 5 years of store-item sales data, and asked to predict 3 months of sales for 50 different items at 10 different stores. For this purpose we set up Lasso regression, MLP and RNN neural networks. To deal with the difficulty in forecasting 90-step ahead, we employ Recursive, Direct, MIMO and DIRMO strategies, respectively. SOme results on Kaggle:

                                   |         Private Score           |      Public Score
-----------------------------------|---------------------------------|-----------------------
Lasso + Recursive Strategy         |           14.34500              |       14.86393
Lasso + Direct Strategy            |           13.32273              |       14.88406
