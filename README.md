# Deep Reinforcement Learning approach using customized Technical Indicators for pre-emerging stock market: A case study of Vietnamese stock market

## Introduction

The Vietnamese stock market is a challenge for applying algorithmic trading. However, the advance of Machine Learning, especially Reinforcement Learning, has provided a new opportunity to develop better trading models. In this work, we proposed an ensemble strategy, namely S-A-P, combining three deep reinforcement learning models (i.e., SAC, PPO, and A2C). The best model at each quarter is used for trading in the incoming quarter based on the Sharpe ratio. Moreover, the list of technical indicators is also proposed to represent the variation in this market. Our approach shows better performance than the baseline and VN30INDEX in both profits (55\% in cumulative return) and risk management (0.77 in Sharpe ratio). Additionally, this approach can perform appropriately during two high-turbulence periods, which the baseline cannot detect. The extension of this work may consider a novel Machine Learning approach for representing the stock market and a different metric for building ensemble strategy.

## Publication

Publisher: 2022 RIVF International Conference on Computing and Communication Technologies (RIVF)

For more information,  please follow this [link](https://ieeexplore.ieee.org/abstract/document/10013836)

## Notes
- Our source code is implemented in the Collaboratory of Google.
- All the necessary libraries and how to install these libraries are presented in our "Source_code.ipynb" file.
- You should upload the "DRL Approach for A Pre-emerging Market" folder to your Google Drive.
- The guide to connecting to your Google Drive is introduced in the source code.
- The flow of running source code: Prepare ---> Data ---> Custom Environment ---> Model ---> Run strategy ---> Run DRL ---> Backtesting.
