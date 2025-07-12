# 🔍 AI Treasure Hunt – Uniform Cost Search on a Hexagonal Grid

![App Preview](SampleOutput.png)

This project simulates an **AI agent navigating a hexagonal grid** world to collect treasures using the **Uniform Cost Search (UCS)** algorithm. The environment includes **traps**, **rewards**, **obstacles**, and **energy constraints**, making the search more realistic and challenging.

This was developed as part of the Artificial Intelligence course project. This was a group project. 

---

## 🌍 Project Description

- The virtual world is represented as a **6x10 hexagonal grid**
- The AI starts from a fixed location and must **collect all treasures**
- Movement incurs cost, affected by:
  - ⚠️ **Traps** (higher cost and energy usage)
  - 🎁 **Rewards** (lower cost and energy usage)
  - ❌ **Obstacles** (cannot pass through)
- The agent has a **limited energy supply (20 units)** to complete its mission

The main objective is to find the **optimal path** (lowest cost) that allows the agent to collect all treasures **before running out of energy**.

---

## 💡 Features

- Uniform Cost Search (UCS) for optimal pathfinding
- Energy consumption tracking (with trap/reward impact)
- Step-by-step path visualization on a **hexagonal honeycomb grid**
- Color-coded map with:
  - 🟪 Traps
  - 🟩 Rewards
  - 🟨 Path taken
  - 🟧 Current node
  - 🪙 Treasures
  - 🪨 Obstacles
- Unicode symbols representing grid effects (⊖, ⊕, ⊞, etc.)
- Automatic alert if energy runs out before finishing

---

## 🎮 How to Run

### Requirements

- Python 3.x
- matplotlib
- numpy

### Steps

```bash
pip install matplotlib numpy
python treasure_hunt_ai.py
