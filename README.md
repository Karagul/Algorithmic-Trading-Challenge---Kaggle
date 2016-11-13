#[Algorithmic Trading Challenge](https://www.kaggle.com/c/AlgorithmicTradingChallenge)
##[Foundations of Machine Learning](http://cs.nyu.edu/courses/fall16/CSCI-GA.2566-001/index.html/)
##CSCI-GA.2566-001
##Term Project

###Introduction
The aim of the Kaggle challenge `Algorithmic Trading Challenge` is to find emprical models to predict market response to large trades. The challenge is already closed and has been picked up for learning purposes and as the term project for the course Foundations of Machine Learning at NYU Courant in Fall 2016.

##Abstract
The aim of the project is to develop empirical predictive models for market response to large trades or more intuitively known as liquidity shock. The large dataset provided by the challenge consists of Training and Test datasets separately containing trade and quote data from London Stock Exchange(LSE) after a liquidity shock. This project analyses and evaluates different models, namely, boosting techniques like AdaBoost[2] and Random Forests[1]. Also, I intend to implement neural networks for the same. 

This dataset is very valuable and maybe used for modelling High Frequency Trading strategies. Hopefully, I will be able to evaluate techniques like Reinforcement Learning [3], Inverse Reinforcement Learning [4]. 

Most of the programming and viasualization would be done through python. Neural Network would be implemented using Torch.

###References

1. [Liaw, Andy, and Matthew Wiener. "Classification and regression by randomForest." R news 2.3 (2002): 18-22.](ftp://131.252.97.79/Transfer/Treg/WFRE_Articles/Liaw_02_Classification%20and%20regression%20by%20randomForest.pdf)
2. [Collins, M., Schapire, R.E. & Singer, Y. Machine Learning (2002) 48: 253. doi:10.1023/A:1013912006537](http://link.springer.com/article/10.1023/A:1013912006537)
3. [Machine Learning for Market Microstructure and High Frequency Trading](https://www.cis.upenn.edu/~mkearns/papers/KearnsNevmyvakaHFTRiskBooks.pdf)
4. [S. Yang et al., "Behavior based learning in identifying High Frequency Trading strategies," 2012 IEEE Conference on Computational Intelligence for Financial Engineering & Economics (CIFEr), New York, NY, 2012, pp. 1-8](http://ieeexplore.ieee.org/document/6327783/?part=1)