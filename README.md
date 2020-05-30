
# Reproducing DeepMind’s MuZero Algorithm on Atari Games

Authors: Madhumitha Sivaraj and David Tian <br/>
Course: CS 536, Machine Learning II (Graduate Course) <br/>
Professor: [Dr. Sungjin Ahn](https://sungjinahn.com/) <br/>
Semester: Spring 2020

Presentation deck can be found [here](https://github.com/madhusivaraj/muzero/blob/master/Presentation%20Deck.pdf). <br>
Final Paper can be found [here](https://github.com/madhusivaraj/muzero/blob/master/Reproducing%20and%20Enhancing%20DeepMind%E2%80%99s%20MuZero.pdf). 

## Description
Games have become one of the most efficient vehicles for evaluating artificial intelligence (AI) algorithms. Agents with tree-based path planning approaches have achieved remarkable successes in artificial intelligence. However, these planning algorithms all rely on knowledge of the environment’s dynamics, such as the rules of the game or an accurate simulator. A team at DeepMind released its MuZero agent which predicts the quantities most relevant to game planning to achieve high performance in complex domains. Intuitively, MuZero internally invents game rules or dynamics that lead to accurate planning. In this paper, we reproduce and enhance the MuZero algorithm and attempt to improve the current training rates and final results of the MuZero algorithm. A common problem in reinforcement learning is the balance between exploration and exploitation. Our goal was to build on the current algorithm in an intuitive manner that would allow it to make more informed choices when choosing which actions to explore.

## Run
```
cd code/
```
- Upload 'muzero_colab.ipynb' to Google CoLab.
- Run file.
