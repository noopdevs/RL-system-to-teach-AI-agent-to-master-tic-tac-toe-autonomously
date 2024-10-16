# Tick-Tack-Toe-RL
The implementation includes dynamic state-value updating mechanisms that continuously allow the agent to refine its strategy based on game outcomes. The Q-function's value iteration process enables the agent to develop sophisticated playing strategies without any pre-programmed game knowledge, purely through experiential learning and reward optimization. Statistical analysis of performance metrics across different player configurations validated the system's learning capabilities and strategic depth, demonstrating the successful implementation of fundamental reinforcement learning principles in a practical game theory context.

# Testing-Environment

Developed a comprehensive multi-agent testing environment supporting both Q-Learning and random agents, enabling rigorous performance analysis across 10,000 game iterations. The system demonstrated remarkable learning efficiency, with the Q-Learning agent achieving an 88% victory rate when playing as the first player against a random opponent. More impressively, when playing as the second player—traditionally a disadvantaged position—the agent achieved a 58% win rate, demonstrating the algorithm's ability to overcome positional disadvantages through strategic learning.

## Files and Folder info
************************

tick-tack-toe.ipynb - A jupyter notebook containing the code for the algorithm. This is an annotated notebook with cells explaning the code and discussing the results. 

board.py - A .py file containing the board. This file prints the board game given the player inputs.

pic1.PNG - A png file used in the jupyter notebook.

## Board Representation
***********************

![pic1](https://user-images.githubusercontent.com/85404022/126875031-6b0d59a4-3901-4709-a8d4-6b81db83dcb1.PNG)

## Results
***********
**Two random agents playing with each other**

![two random agents](https://user-images.githubusercontent.com/85404022/126875121-2a83b8a2-7a4f-4add-be22-9e18466b04f9.png)


**RL agent and a random agent playing with each other (The RL agent is always playing first in this scenario)**

![download](https://user-images.githubusercontent.com/85404022/126875135-064b80e9-3812-4d07-8102-390990d2c4d7.png)

![download (1)](https://user-images.githubusercontent.com/85404022/126875146-f61fd3a6-da78-48b6-838d-030fb10518cf.png)


**Random agent and a RL agent playing with each other (The random agent is always playing first in this scenario)**

![download (2)](https://user-images.githubusercontent.com/85404022/126875163-d8e493e7-4987-4313-a0f2-a21d240f14c9.png)

![download (3)](https://user-images.githubusercontent.com/85404022/126875167-7727b1e5-8b82-4de9-b762-738845840d67.png)

**RL agent and RL agent playing with each other**

![rl vs rl](https://user-images.githubusercontent.com/85404022/129118393-395eaad3-25ce-42fc-9df7-eec761114918.png)

![download (5)](https://user-images.githubusercontent.com/85404022/126875190-d6599370-085c-425d-b471-2a7b738147a2.png)


## Future work
**************

- Use different exploration, learning rate, discount values

- Will try to use deep RL to see if how the results change. 
