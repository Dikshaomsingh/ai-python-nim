In the game Nim, we begin with some number of piles, each with some number of objects. Players take turns: on a player’s turn, the player removes any non-negative number of objects from any one non-empty pile. Whoever removes the last object loses.

In this project, AI will learn the strategy for this game through reinforcement learning. By playing against itself repeatedly and learning from experience, eventually our AI will learn which actions to take and which actions to avoid.

algorithm used: Q-learning

Q(s, a) ⟵ Q(s, a) + α(new value estimate - Q(s, a))
Q(s, a) = outputs an estimate of the value of taking action a in state s
new value estimate = sum of the reward (r) and the future reward estimate
