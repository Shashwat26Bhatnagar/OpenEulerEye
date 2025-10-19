# Euler's Eye  
**Team Vertex - Track 2**

---

## Project Overview  
Euler's Eye is a concise and easy-to-use monitoring system for the OpenEuler OS that tracks system vitals in real-time, including CPU usage, Network I/O, and more.  

The system is enhanced with a predictive AI model designed to estimate the cache miss rate, aiming to improve user experience by optimizing cache replacement policies.  

Our approach treats the cache replacement problem as a Markov Decision Process (MDP) and leverages Deep Reinforcement Learning, specifically a value-based Deep Q Network (DQN), to learn and optimize these strategies.

---

## Features  
- Real-time monitoring of system vitals (CPU, Network I/O, etc.)  
- Predictive modeling of cache miss rates  
- Learning-based cache replacement policies using Deep Q Networks  
- Intuitive web UI for live metric visualization  

---

## Team Members  
- Aarav Parin  
- Rory Condict  
- Shashwat Bhatnagar  
- Zeki Kam  
- Zarif Ahmed  

---

## Usage Guide  

### 1. Generating Miss Rate Predictions  
- Ensure you have data available in CSV format.  
- Preprocess the data to reduce the number of features.  
- Run the prediction script:  
  ```bash
  python3 run_openeuler_filesys.py
