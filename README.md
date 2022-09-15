# CliffWalkingAgent

## The Agents
There are two agents presented in this repository, one as a sample case (the random agent found in the **cliff_random.py** file) and one as a basic exercise in reinforcement learning (the Q-Agent found in the **cliff_qagent.py** file).

1. The first model, found in the **cliff_random.py** file, selects a random action from the action space (found with the **env.action_space.sample()** function provided by Gym) for the agent to take given an environment. As a result, the agent takes a vast number of steps to ultimately reach the desired destination without falling off the cliff.

2. The second model, found in the **cliff_qagent.py** file, selects a random action based on a Q-Table that is updated every epoch during the training processs according to the Q-Table updating equation. The Q-Table has dimensions of 500 x 4 for 4 action spaces and 

## Hyperparameters

## The Environment
The environment is provided by OpenAI's Gym package (linked below) under the package's *Toy Text Environments*. The environment provides a reward of ...
## Libraries
