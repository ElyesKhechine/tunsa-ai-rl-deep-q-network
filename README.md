# Optimizing Cart Pole Stability with Deep Q-Learning

### TUNSA AI

**Technologies:** Python, TensorFlow, Keras, Keras-RL, OpenAI Gym, Numpy, CartPole-v0, DQN, Boltzmann Policy, Dopamine-RL

## Introduction

This project focuses on leveraging advanced reinforcement learning techniques to enhance the stability of a pole balanced on a moving cart within the CartPole-v0 environment. It involved rigorous experimentation and optimization of deep Q-learning algorithms.


## Project Scope

 This project was undertaken by the Tunisian Space Association (TUNSA)'s AI team from October 9, 2022, to November 13, 2022.

## Technical Details

- **Reinforcement Learning Model**: Developed a robust TensorFlow and Keras-based reinforcement learning model capable of stabilizing the cart pole system within the CartPole-v0 environment.
- **Neural Network Architecture**: Designed a neural network architecture comprising 3 layers, fine-tuning 770 parameters to effectively classify 4D input states, resulting in a 14% faster training convergence.
- **Deep Q-Network (DQN) Agent**: Implemented a DQN agent using Keras-RL and a Boltzmann policy, training it for 50,000 steps and achieving an average episode reward of 42.6 over 100 test episodes.
- **Model Refinement**: Iteratively refined model parameters and hyperparameters, leading to a 19% reduction in mean absolute error and achieving a 93% success rate in stability over five test episodes.

### Project Colab Link

Access the project's [Google Colab notebook](https://colab.research.google.com/drive/172mY-dbLJq484xGz-Yb_O1vUNVuuWbVX) for implementation details and experimentation.

## License

This project is licensed under the [GPL-3.0 License](LICENSE).

## Contacts

For inquiries or collaboration opportunities, please contact:

- Elyes Khechine: elyeskhechine@gmail.com
