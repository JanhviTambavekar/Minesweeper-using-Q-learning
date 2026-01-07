# Minesweeper-using-Q-learning
# 🧠 Minesweeper AI using Q-Learning

An intelligent **Minesweeper game with an AI agent** trained using **Q-Learning**, featuring a clean glassy UI built with **Pygame**.  
This project demonstrates how **Reinforcement Learning** can be applied to decision-making under uncertainty.

---

## 📌 Project Overview

Minesweeper is a classic problem involving incomplete information and risk assessment.  
In this project, an AI agent learns to play Minesweeper by interacting with the environment, receiving rewards for safe moves, and penalties for hitting mines.

### Project Goals
- Apply **Reinforcement Learning (Q-Learning)** to a real game environment  
- Maintain **constant mine count and fixed mine positions** for stable learning  
- Preserve the **Q-table across levels** to enable continuous improvement  
- Provide a **visual and interactive UI** to observe AI behavior  

---

## 🎮 Features

- 🤖 Q-Learning based AI agent  
- 💣 Constant mine count across all levels  
- 🧠 Persistent learning (Q-table retained across games)  
- 📈 Curriculum learning (progressive difficulty)  
- 🖥️ Glassy Pygame UI with side statistics panel  
- 📊 Live stats: score, win ratio, level, mine count  
- ⏱️ Adjustable AI execution speed  

---

## 🧠 AI Details

- **Algorithm:** Q-Learning  
- **Exploration Strategy:** ε-greedy  
- **State Representation:** Local cell observations  
- **Action Space:** Selecting unrevealed cells  
- **Reward Strategy:**
  - Safe move → positive reward  
  - Hitting a mine → negative reward  
  - Winning a game → bonus reward  

This setup allows the agent to gradually learn safer and more optimal strategies.

---

## 🗂️ Project Structure

