This is my little study for deep reinforcement learning on stocks during the MADS program at UM. I found that most of the repositories are moduled programs, which may not be easy for beginners to follow. Therefore, I code these programs in Jupyter Notebook.

# Discrete Space
For DQN, DDQN, and other RL models for discrete space, the RL model works on a single stock/index. The action space is the position, which is 0% - 100%, representing the market value of the stock and total assets.

If you are interested in trying different indicators, the only thing needed is to add them into stock_df, and change the variable indicators. 'open' and 'close' are needed in the DataFrame to calculate the returns. The data should be like this:
![image.png](https://github.com/duowenpu/Reinforcement-Learning-for-Stock-Investment/blob/master/image.png)

If you are interested in changing the time frequency, just keep them in order.

# Continuous Space
To be updated.

**I would add more notebooks and backtest code before middle December.**