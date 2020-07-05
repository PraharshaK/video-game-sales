## [Predicting the Sales of Video Games](https://github.com/PraharshaK/video-game-sales/blob/master/README.md)

### Overview

The gaming industry is certainly one of the thriving industries of the modern age and one of those that are most influenced by the advancement in technology. With the availability of technologies like AR/VR in consumer products like gaming consoles and even smartphones, the gaming sector shows great potential. 
The main objective is to estimate the sales of video game sales.


![](https://github.com/PraharshaK/video-game-sales/blob/master/publisher%20sales.JPG)

[Year wise distribution of sales](https://github.com/PraharshaK/video-game-sales/blob/master/year%20wise%20sales%20distribution.JPG)


Data consists of 8 distinguishing factors that can influence the sales of a particular video game. The data is available [here](https://www.kaggle.com/kpraharsha/sdgfasd) you can download and try some more EDA and feature engineering to improve the model performance.


In this notebook, I have ensembled best performing algorithms together for better results, but interestingly in this case [CATBOOST](https://catboost.ai/docs/concepts/about.html) alone have performed much better.


This model works prety much good, as the error is 1.69 RMSE score. You can check how it is calculated [here](https://www.statisticshowto.com/probability-and-statistics/regression-analysis/rmse-root-mean-square-error/)

I recommend using colab or kaggle notebooks as they offer GPU for limited time per week for faster execution.
Simply change runtime in notebook setings by: runtime -> change runtime type -> gpu
