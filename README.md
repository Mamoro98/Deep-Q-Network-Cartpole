
# 🚀 Deep-Q-Network for CartPole 🏋️‍♂️

This repository contains an implementation of a **Deep Q-Network (DQN)** to solve the **CartPole-v1** environment in Reinforcement Learning. The goal is for the agent to learn how to balance a pole on a cart for as long as possible. 🛠️

## 📂 Project Structure

```
Deep-Q-Network-Cartpole/
│
├── cartpole.ipynb    # Jupyter notebook with DQN implementation
└── README.md         # Project overview (this file)
```

## 🎯 Objectives

- Learn to solve the **CartPole-v1** environment using Deep Reinforcement Learning. 🧠
- Implement key components of DQN:
  - Q-Network 🖥️
  - Replay Buffer 🔁
  - -greedy action selection 🎲
- Achieve a perfect score of 500 in the environment. 🏆

## 🛠️ Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Mamoro98/Deep-Q-Network-Cartpole.git
   cd Deep-Q-Network-Cartpole
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the notebook**:
   Launch `cartpole.ipynb` in your favorite Jupyter environment:
   ```bash
   jupyter notebook cartpole.ipynb
   ```

## 🧑‍💻 Features

- **Dynamic Q-Learning**: Neural networks approximate the Q-value function. 🧮
- **Replay Buffer**: Efficient experience replay to stabilize learning. 🔄
- **Adaptive Exploration**: -greedy action selection with a decaying epsilon. 🌟

## 📈 Performance

- The model is trained to solve CartPole by maximizing rewards over episodes.
- **Evaluation**: The agent achieves a consistent episode return of 500.
- Video: https://github.com/user-attachments/assets/326624dd-d382-4def-8e2d-3f3287535c5e



## 🏛️ License

This project is licensed under the **Apache License 2.0**. See the `LICENSE` file for more details.

## 💬 Acknowledgments

Special thanks to:
- **Arnu Pretorius**: Staff Research Scientist at InstaDeep. ✨
- **AIMS South Africa**: African Institute for Mathematical Sciences. 🌍

---
