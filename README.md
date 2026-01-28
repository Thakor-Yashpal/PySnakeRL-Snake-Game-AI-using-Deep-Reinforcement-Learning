# PySnakeRL-Snake-Game🐍-AI-using-Deep-Reinforcement-Learning

SnakeRL is a Reinforcement Learning project where an AI agent learns to play the classic Snake game using **Deep Q-Learning (DQN)**.  
The game is built with **Pygame**, and the neural network is implemented using **PyTorch**.

The agent improves over time by interacting with the environment, learning optimal actions through rewards and penalties.

---

## 🚀 Features

- Classic Snake game implemented in **Pygame**
- AI agent trained using **Deep Q-Networks (DQN)**
- Neural network built with **PyTorch**
- Experience Replay for stable training
- Epsilon-greedy strategy for exploration vs exploitation
- Real-time visualization of the training process
- Score tracking and performance improvement over episodes

---

## 🧠 How It Works

1. The Snake game acts as the **environment**
2. The AI agent observes the current **state** (snake direction, food position, danger zones)
3. The agent chooses an **action** (straight, left, right)
4. A **reward** is given:
   - + reward for eating food
   - - penalty for collision
5. The neural network updates using **Q-learning**
6. Over time, the agent learns to survive longer and score higher

---

## 🛠️ Tech Stack

- **Python**
- **PyTorch**
- **Pygame**
- **NumPy**

---

## 📂 Project Structure

```text
SnakeRL/
│
├── agent.py          # DQN agent logic
├── model.py          # Neural network model
├── game.py           # Snake game environment (Pygame)
├── train.py          # Training loop
├── utils.py          # Helper functions
├── requirements.txt  # Dependencies
└── README.md
