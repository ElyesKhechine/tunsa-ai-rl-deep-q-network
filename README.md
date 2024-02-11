# Optimizing Cart Pole Stability with Deep Q-Learning

### TUNSA AI

**Technologies:** Python, TensorFlow, Keras, Keras-RL, OpenAI Gym, Numpy, CartPole-v0, DQN, Boltzmann Policy, Dopamine-RL

## Introduction

This project, undertaken by TUNSA AI, focuses on developing a robust reinforcement learning model for stabilizing a pole on a moving cart within the CartPole-v0 environment. Leveraging state-of-the-art Q-learning methodologies, this project aims to enhance training convergence and stability performance.

## Project Scope

Commencing from October 9, 2022, to November 13, 2022, the project underwent thorough research, development, and testing phases.

### Project Colab Link

Access the project's Google Colab environment for code implementation and experimentation: [Project's Google Colab](https://colab.research.google.com/drive/172mY-dbLJq484xGz-Yb_O1vUNVuuWbVX)

## Technical Details

- **Neural Network Architecture Optimization**: Development of a neural network architecture with three layers and fine-tuning of 770 parameters to effectively classify 4D input states, resulting in a 14% faster training convergence.
- **Deep Q-Learning Agent Implementation**: Utilization of Keras-RL to implement a Deep Q-Network (DQN) agent with a Boltzmann policy, trained over 50,000 steps, achieving an average episode reward of 42.6 over 100 test episodes.
- **Model Parameter Refinement**: Iterative refinement of model parameters and hyperparameters, leading to a 19% reduction in mean absolute error and a 93% success rate in stability over five test episodes.

## Contributing

Contributions aimed at further optimizing model performance and exploring advanced techniques in reinforcement learning are welcome.

## License

This project is licensed under the [GPL-3.0 License](LICENSE).

## Contacts

For inquiries or collaboration opportunities, please contact:

- Elyes Khechine: elyeskhechine@gmail.com
