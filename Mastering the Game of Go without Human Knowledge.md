# AlphaGo Fan
1. defeated the European champion Fan Hui in October 2015
2. a policy network that outputs move probabilities, and a value network that outputs a position evaluation
3. The policy network was trained initially by supervised learning to accurately predict human expert moves, 
and was subsequently refined by policy-gradient reinforcement learning. The value network was trained to 
predict the winner of games played by the policy network against itself.

# AlphaGo Zero
1. it is trained solely by self-play reinforcement learning, starting from random play, without any 
supervision or use of human data.
2. it only uses the black and white stones from the board as input features
3. it uses a single neural network
4. it uses a simpler tree search that relies upon this single neural network to evaluate positions and 
sample moves, without performing any Monte-Carlo rollouts
5. introduce a new reinforcement learning algorithm that incorporates lookahead search inside the training loop, 
resulting in rapid improvement and precise and stable learning


