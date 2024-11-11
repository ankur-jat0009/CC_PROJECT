# Online Partial Offloading and Task Scheduling in SDN-Fog Networks Using Deep Recurrent Reinforcement Learning

## Project Overview

This project implements a **Deep Recurrent Q-Network (DRQN)** to optimize task scheduling and offloading in **SDN-enabled Fog Networks**. The model leverages **partial offloading** and **deep reinforcement learning** to manage network resources dynamically, reduce latency, and enhance task efficiency in a fog computing environment.

## Key Features

- **SDN-Fog Integration**: Combines SDN with fog computing to enable flexible, real-time network resource allocation.
- **Partial Offloading**: Splits tasks between local and remote processing for optimal energy use and latency reduction.
- **Task Scheduling**: Dynamically allocates offloaded tasks to fog nodes based on real-time network conditions.
- **Deep Recurrent Reinforcement Learning (DRRL)**: Uses LSTM-based Q-Network for handling temporal dependencies, optimizing task offloading, and improving decision-making based on sequential data.

## Table of Contents

- [Core Concepts](#core-concepts)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Output Examples](#output-examples)
- [Conclusion and Future Work](#conclusion-and-future-work)
- [References](#references)
- [Authors](#authors)

## Core Concepts

- **Software-Defined Networking (SDN)**: SDN provides centralized control to fog networks, enabling programmable data flow and resource allocation adjustments.
- **Fog Computing**: Brings computation closer to IoT devices, reducing latency and enabling efficient local processing.
- **Types of Offloading**: Includes partial, full, adaptive, and delay-tolerant offloading strategies to balance resource use and latency.
- **Deep Recurrent Q-Network (DRQN)**: Incorporates LSTM layers to manage sequential data and dynamic network conditions, improving task scheduling in a partially observable environment.

## Project Structure

```plaintext
├── models/
│   ├── drqn_model.py        # DRQN model architecture
├── env/
│   ├── fog_environment.py   # Fog environment simulation
├── training/
│   ├── train.py             # DRQN model training script
├── evaluation/
│   ├── eval.py              # Performance evaluation script
├── utils/
│   ├── replay_buffer.py     # Experience replay buffer for DRQN training
├── outputs/
│   ├── results/             # Log files and results of experiments
└── README.md
