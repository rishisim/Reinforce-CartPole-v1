In policy-based methods, we directly learn to approximate the optimal policy $\pi ^ *$ without having to learn a value function. We parameterize the policy by using an neural network which will output a probability distribution over actions (Stochastic Policy). Policy-gradient methods is a subclass of policy-based methods in which we search directly for the optimal policy. We optimize the parameter directly by performing the gradient ascent on the performance of the objective function.

The Reinforce algorithm, also called Monte-Carlo policy-gradient, is a policy-gradient algorithm that uses an estimated return from an **entire episode** to update the policy parameter $\theta$. The following is an implementation of the Reinforce algorithm in the CartPole-v1 environment.

# Results
Mean_Reward: 500 +/- 0.00

https://github.com/rishisim/Reinforce-CartPole-v1/assets/86998121/e4799de9-460a-49c0-a7b5-bb08faa44b32


tags:
- CartPole-v1
- reinforce
- reinforcement-learning
- custom-implementation
- deep-rl-class
model-index:
- name: Reinforce-CartPole-v1
  results:
  - task:
      type: reinforcement-learning
      name: reinforcement-learning
    dataset:
      name: CartPole-v1
      type: CartPole-v1
    metrics:
    - type: mean_reward
      value: 500.00 +/- 0.00
      name: mean_reward
      verified: false
---

  # **Reinforce** Agent playing **CartPole-v1**
  This is a trained model of a **Reinforce** agent playing **CartPole-v1** .
  To learn to use this model and train yours check Unit 4 of the Deep Reinforcement Learning Course: https://huggingface.co/deep-rl-course/unit4/introduction
  
