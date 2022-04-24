# Reinforcement-Learning-
In this, I have named my environment as Knight Raider which is kind of a simulation of horse in
forest in search of carrots. The environment consists the following actions, states, terminal state,
and rewards:
• Actions: {Left, Right, Backward, Forward , Diagonal }
• States: 64 states with one starting point and one terminal state.
• Rewards: {-2,-1,5,6,5,100}
• Action Probability: 100%
The agent is allowed to move in any direction in the forest where diagonal movement is restricted
to one direction. The agent is on the one end of the forest and is in search of food which is the goal.
There are hay stacks that can be found on some locations in the forest, which can be found in the
search of final goal. If the agent is able to find hay stock, it gets a reward. If in case, the agent
encounters sugar, it will get negative reward. If the agent makes it up to the carrots, the episode
will end and the agent gets best positive reward. Ultimate objective of this setup for the agent is to
collect maximum rewards.
