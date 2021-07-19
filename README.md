# RL Portfolio


## Tips
+ DDPG.ipynb: Run this notebook to train and test DDPG-based portfolio as baseline
+ QFPIS-1.ipynb: Run this notebook to train and test using one Quantum price level(QPL)
+ QFPIS-2.ipynb: Run this notebook to train and test using two QPL
+ backtest.ipynb: Run this notebook to do back test
+ ./data: Contain the training and testing data
+ ./environment: Contain the reinforcement learning enviroment:1)QF_env: enviroment for DDPG 2）QF_env_1: environment for QFPIS-1 3) environment for QFPIS-2
+ ./model: Contain the trained models
+ ./config/config.json: configure the training settings:
```
{
  "episode": 100,
  "max step": 1000,
  "buffer size": 100000,
  "batch size": 64,
  "tau": 0.001,
  "gamma": 0.99,
  "actor learning rate": 0.0001,
  "critic learning rate": 0.001,
  "policy learning rate": 0.0001
}
```
## TODO
+ GPU/TPU Only
+ Change Forex to Crypto Data, Top 20 Volume
+ Training 2018-2020/ Testing 2021
+ All data features training
+ Up to 10 QPL instead 2
+ Backtest 
+ Future: Implement on terminal. Compare with AlphaZero 
