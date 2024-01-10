Experimenting with RL for building optimal portfolio of 3 stocks and comparing it with portfolio theory based Markowitz' approach



To train RL model:
```
python train.py
```

Take a look at pre_process.py if you want to get an idea on how this file was cleaned and compiled.


## Problem Statement

I will be formulating this as a portfolio optimization problem : 
Given histories of 3 different stocks, how would we allocate a fixed amount of money between these stocks every day so that maximize the likelihood of returns. 

The objective is to develop of policy (strategy) for building a portfolio. The portfolio is essentially an allocation of available resources across various stocks. The policy then needs to restructure the portfolio over time as new information becomes available.
















