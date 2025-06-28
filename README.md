# Peer-to-Peer Energy Trading Platform

## Overview
This project implements a decentralized peer-to-peer (P2P) energy trading platform, allowing prosumers (both buyers and sellers) to trade energy efficiently. The platform integrates multi-objective optimization (NSGA-II) for maximizing welfare and ensures network feasibility using node voltage calculations to verify energy transaction validity.

## Features
- **Multi-Objective Optimization (NSGA-II)**: Maximizes welfare for buyers and sellers in the energy market.
- **Network Stability Check**: Ensures feasibility of energy transactions using Backward-Forward Sweep (BFS) analysis of node voltages.
- **Time-Based Energy Allocation**: Divides the day into specific time frames to optimize energy allocation based on user preferences.
- **Decentralized Energy Trading**: Empowers prosumers to trade energy directly, cutting out intermediaries.

## Technologies Used
- **Python Django**: Backend framework for developing the platform.
- **NSGA-II Optimization**: Used for solving the multi-objective optimization problem.
- **Backward-Forward Sweep (BFS)**: Ensures network feasibility by analyzing node voltages.
- **NumPy/Pandas**: Data handling and calculations for energy allocation and optimization.

### Prerequisites
- Python
- NumPy
- Pymoo

## Usage
1. Prosumers submit energy bids/offers through the platform interface.
2. The optimization algorithm (NSGA-II) runs to clear the market and maximize welfare for all parties.
3. After the optimization, the network feasibility is checked using BFS analysis to ensure that energy transactions are valid.
4. Energy is allocated to buyers and sellers based on feasibility and predefined time frames.

## Future Enhancements
- **Diversification of Buyers**: Include high and ultra-high demand buyers to create a more dynamic market.
- **Blockchain Integration**: Use blockchain technology to implement a digital ledger for secure, transparent, and tamper-proof energy transactions.
- **Real-Time Settlement**: Implement ex post transactions for real-time settlement of energy trades to improve market efficiency and accuracy.
