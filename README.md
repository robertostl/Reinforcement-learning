#Reinforcement learning techniques for dynamic pricing
Code from the final project of the Master Course.

The main propose of this work is to study different techniques of reinforcement learning in order to
solve some dynamic pricing problems.

We study the fundamentals of reinforcement learning for a single agent and
we see four algorithms for this type of problems: Q-Learning, SARSA, Double Q-Learning and Expec-
ted SARSA. Reinforcement learning is an area of machine learning whose aim is to know how agents
should take actions in an environment. In the case of a single agent, it is estructured as a Markov de-
cision process. Markov decision process is an extension of Markov chains and is essentially defined
by a state space, an action space and transition probabilities, (S,A,P). This framework provides some
useful optimallity statements by the definition of value functions: state-value function and action-value
function types of algorithms are model-based and free-models, we focus on model free algorithms, in particular
the ones who use temporal difference learning.

We analyse the results of some dynamic pricing problems solved with reinforcement
learning. The first problems have a single agent fixing prices on each month, we have three products
with differents demands and a specific inventory level for each product. The goal is to maximize the
revenue taking into account the avaliable periods of sales and the storage cost. We compare the results
taking a stochastic demand in the training or a deterministic demand. The other type of problems have
two agents competing for the sales of the same product. We consider two circumstances, that there is an
agent who is not influenced by other’s prices and the case that the two agents are mutually influenced
by their prices.
