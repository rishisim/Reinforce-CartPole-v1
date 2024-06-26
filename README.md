# Overview: Policy-Based Methods
In policy-based methods, we directly learn to approximate the optimal policy $\pi ^ *$ without having to learn a value function. We parameterize the policy by using an neural network which will output a probability distribution over actions (Stochastic Policy). Policy-gradient methods is a subclass of policy-based methods in which we search directly for the optimal policy. We optimize the parameter directly by performing the gradient ascent on the performance of the objective function.

# Reinforce Algorithm
The Reinforce algorithm, also called Monte-Carlo policy-gradient, is a policy-gradient algorithm that uses an estimated return from an **entire episode** to update the policy parameter $\theta$. The following is an implementation of the Reinforce algorithm in the CartPole-v1 environment.

# Results
Mean_Reward: 500 +/- 0.00

https://github.com/rishisim/Reinforce-CartPole-v1/assets/86998121/e4799de9-460a-49c0-a7b5-bb08faa44b32
