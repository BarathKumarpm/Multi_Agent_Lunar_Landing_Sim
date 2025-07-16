# 🛰️ Multi-Agent Lunar Lander Simulation using Reinforcement Learning

A simulation environment inspired by OpenAI Gym and PettingZoo that explores autonomous coordination between **two lunar landers** attempting simultaneous touchdowns. This project focuses on extending the traditional single-agent Lunar Lander task to a **multi-agent reinforcement learning (MARL)** scenario — introducing complexity, real-time cooperation, collision avoidance, and fuel optimization.

---

## 📘 1. Introduction

**Multi-Agent Lunar Lander** is an advanced version of the classical Lunar Lander environment built using **OpenAI Gymnasium (Box2D)** and the **PettingZoo** framework. Instead of controlling a single lander, this project introduces two landers that must coordinate to land safely — transforming the task from a single-agent control problem into a **multi-agent coordination challenge**.

Agents must manage:
- Independent and interdependent controls
- Thrust, orientation, fuel optimization
- Inter-agent interference and stability management

The simulation resembles **real-world scenarios** such as:
- Coordinated landings of autonomous spacecraft
- Drone fleet coordination
- Multi-robot system control in unstructured environments

---

## 🚩 1.2 Problem Statement

In future space missions, simultaneous landings of multiple landers on the Moon could help reduce costs via:
- Shared payload capacity
- Rideshare opportunities
- Reusability

However, this approach increases:
- Navigational complexity
- Development cost for hazard avoidance and control systems
- Risk of interference and failure

This simulation environment allows for experimentation and training of agents under such constraints, enabling researchers to optimize for cost, safety, and performance.

---

## 🎯 1.3 Objectives

The project’s objectives include:
- Simulating safe and fuel-efficient landings in a multi-agent scenario
- Designing adaptive control strategies using reinforcement learning
- Building agents that generalize across dynamic conditions and unforeseen environmental states
- Benchmarking various RL algorithms using performance metrics such as:
  - Landing success
  - Fuel efficiency
  - Collision avoidance
  - Time-to-land

---

## ✅ 1.4 Benefits of Simultaneous Multi-Lander Missions

- **Cost Efficiency**: Reduces need for redundant backup systems
- **Mission Reliability**: Promotes robust risk assessment and coordination
- **Improved Precision**: Helps test real-time autonomous landing under limited zone constraints
- **Scalability**: Encourages multi-lander, multi-mission automation

> Synchronization between landers is crucial — failure in coordination can increase mission time and operational costs.

---

## 🔭 1.5 Scope of the Project

This project:
- Converts OpenAI’s single-agent Lunar Lander into a **multi-agent PettingZoo-compatible environment**
- Simulates real-world lunar dynamics such as:
  - Irregular terrain
  - Varied soil types
  - Light and gravity conditions

### Key Features:
- **Dual-agent control** with independent and shared policy learning
- **Custom reward functions** for balancing:
  - Safe landing
  - Fuel use
  - Synchronization
  - Collision avoidance
- **Parameter tuning** for different operation scenarios
- **Modular design** for research extensibility and reproducibility

---

## 🛠️ Technologies & Tools

- `OpenAI Gym`
- `PettingZoo`
- `Box2D`
- `Stable-Baselines3`
- `Python 3.x`
- `NumPy`, `Matplotlib`, etc.

---

## 📈 Real-World Inspiration

Inspired by **NASA's CADRE and AAMAS projects**, which explore decentralized coordination among autonomous robotic landers.

---

## 🤝 Contributions & Future Work

We welcome contributions! Potential extensions:
- Inter-agent communication modeling
- Competitive vs cooperative multi-agent settings
- Integration with real-world sensor data

---

## 📄 License

This project is open-sourced under the MIT License.

---

## 🌌 Final Note

Multi-Agent Lunar Lander provides a challenging yet promising platform for advancing reinforcement learning in space robotics, autonomous control, and multi-agent systems. Through research and collaboration, this project aims to serve as a testbed for future intelligent space missions.

