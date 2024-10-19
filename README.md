# ⚛ Optimization of Reinforcement Learning with Quantum Computation ⚛

## 📖 Project Overview

This project focuses on optimizing classical Reinforcement Learning (RL) techniques using Quantum Computation. We leverage RL algorithms with quantum circuits, such as Variational Quantum Circuits (VQCs), to enhance learning in RL environments. The primary goal is to investigate how Quantum Computing can help achieve space optimization in terms of parameters and potentially allow better performance compared to classical approaches.

### ❄ Frozen Lake Environment
![Frozen Lake](./Images/frozen_lake.gif)

This environment involves navigating across a frozen lake without falling into holes, optimizing the policy to avoid dangers.

### 🛤 Cartpole Environment
![Cartpole](./Images/cart_pole.gif)

Cartpole is a classic environment where the goal is to balance a pole on a moving cart, perfect for testing control and RL algorithms.

### 🚀 Lunar Lander Environment
![Lunar Lander](./Images/lunar_lander.gif)

In the Lunar Lander environment, the agent must land a spaceship safely on the moon. It's great for more complex RL experiments with continuous actions.

## 🔍 Key Features:
- Background information on Classical RL and Quantum Computation
- Literature Survey on Existing approaches to QRL
- Implementation of Quantum-enhanced RL using VQC for various OpenAI gym environments.
- Comparative analysis between Classical RL and Quantum RL.
- Performance evaluation using rewards and parameter space optimization.

---

## 📁 Repository Structure

```bash
.
├── Background_Knowledge/                           # Background Knowledge on Topics
├── Literature_Survey/                              # Survey on Existing Literature
├── Code/                                           # Survey on Existing Literature
│   ├── Cart Pole/                                  # Cart Pole Implementation Directory
│   │   └── Cart Pole Policy VQC-DQN/
│   ├── Frozen Lake/                                # Frozen Lake Implementation Directory
│   │   ├── Frozen Lake VQC Q Learning/
│   │   └── rozen Lake Policy VQC-DQN/
│   ├── Lunar Lander/                               # Lunar Lander Implementation Directory
│   │   ├── Lunar Lander Advantage Actor Critic/
│   │   └── Lunar Lander Policy VQC-DQN/
│   └── requirements.txt                            # Requirements file
├── Images/                                         # Images Compilation          
└── README.md                                       # Project description and instructions

```

## 💻 Package installation instructions

1. **Clone the repository**:

```bash
git clone https://github.com/NischalRBhat/Optimization-of-Reinforcement-Learning-using-Quantum-Computation.git
cd Optimization-of-Reinforcement-Learning-using-Quantum-Computation
```

2. **Create a Virtual Environment (optional)**:

```bash

# For Windows
python -m venv env
env\Scripts\activate

# For macOS/Linux
python3 -m venv env
source env/bin/activate
```

3. **Install the dependencies**:

```bash
pip install -r Code/requirements.txt
```

4. **Verify the installation**:

```python
import pennylane, torch, gym, tqdm, qiskit, imageio, numpy, matplotlib
print(pennylane.__version__, torch.__version__, gym.__version__, tqdm.__version__, qiskit.__version__,imageio.__version__, numpy.__version__, matplotlib.__version__)
```
