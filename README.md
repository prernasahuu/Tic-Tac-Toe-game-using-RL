# Tic-Tac-Toe-game-using-RL
 I have build a Basic 3x3 grid, Tic-Tac-Toe game, using Q Learning algorithm.
# Q Learning Algorithm:
  Q-learning is a popular model-free reinforcement learning algorithm used in machine learning and artificial intelligence applications. The learning enables an agent (a computer program)    to learn the best decisions in various situations by interacting with an environment.
### -------------------------------------------------------------------------------------------------------------------------------------------------------------------
## The key components of Q-learning include:
1. Agents: Entities that operate within an environment, making decisions and taking actions.
2. States: Variables that identify an agent’s current position in the environment.
3. Actions: Operations undertaken by the agent in specific states.
4. Rewards: Positive or negative responses provided to the agent based on its actions.
5. Episodes: Instances where an agent concludes its actions, marking the end of an episode.
6. Q-values: Metrics used to evaluate actions at specific states.
### ---------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Methods for Determining Q-Values:
1. Temporal Difference: It is calculated by comparing the current state and action values with the previous ones.
2. Bellman’s Equation: A recursive formula invented by Richard Bellman in 1957, used to calculate the value of a given state and determine its optimal position. It provides a recursive formula for calculating the value of a given state in a Markov Decision Process (MDP) and is particularly influential in the context of Q-learning and optimal decision-making.
Q(s,a)=R(s,a)+γmaxQ(s’,a)
3. SARSA (State-Action-Reward-State-Action): SARSA technique,is an On Policy and uses the action performed by the current policy to learn the Q-value.
Q(s_{t},a_{t}) = Q(s_{t},a_{t}) + \alpha (r_{t+1}+\gamma Q(s_{t+1},a_{t+1})-Q(s_{t},a_{t}))
## Implementation of Q learning:
1. Build an environment.
2. Set hyperparameters.
3. Trained the agent (self play).
4. extracted the Q table.
5. Matched between Agent and Human Player.
### ------------------------------------------------------------------------------------------------------------------------------------------------------
## Results:
approximations: Agent wins 70% matches.
                Human wins 30% matches.
                Draws 10%.
### ----------------------------------------------------------------------------------------------------------------------------------------------------------
## Advantages of Q Learning: 
1. No Prior Knowledge Required :
   Q-learning is a model-free reinforcement learning method, meaning it doesn’t require explicit game strategies or rules. The AI learns optimal moves simply by playing and updating Q-values.
2. Exploration and Exploitation Balance:
    Using epsilon-greedy exploration, the AI balances exploring new moves (to discover better strategies) and exploiting known good moves (to maximize wins).
3. Learning from Experience:
   The AI continuously improves by self-playing and updating Q-values, getting better over time without requiring human intervention.

