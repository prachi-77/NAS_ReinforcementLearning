# Neural Architecture Search (NAS) with Q-Learning

This notebook demonstrates how Q-Learning, a reinforcement learning technique, can be used for Neural Architecture Search (NAS) to improve the performance of a FashionMNIST CNN model.

## Key Steps in This Notebook:

### 1. Train a Baseline CNN Model:
- Load and preprocess the FashionMNIST dataset.
- Define and train a simple CNN model.
- Evaluate and visualize the initial model performance.

### 2. Define the Q-Learning Setup:
- Define the state space (different CNN architectures).
- Define the action space (modifying filter size, kernel size).
- Initialize the Q-table randomly.

### 3. Implement Q-Learning for NAS:
- Use an epsilon-greedy policy to balance exploration and exploitation.
- Iterate over 10 episodes to update architectures based on validation accuracy.
- Update the Q-table using the Bellman equation.

### 4. Visualizations and Results:
- Compare the pre-NAS and post-NAS architectures.
- Display the Q-table evolution over episodes.
- Show improvements in model accuracy.

By the end of this notebook, you will see how Q-learning helps dynamically search for an optimal CNN architecture to improve classification performance on FashionMNIST.
