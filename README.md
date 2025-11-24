# Enhanced Timed Automata Network Scheduler with Real-Time Animation

![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.0%2B-150458?logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7%2B-11557c?logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.3%2B-F7931E?logo=scikit-learn&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

> **A real-time priority-based packet scheduler using Timed Automata with preemptive scheduling, machine learning-driven dynamic deadlines, and stunning animated visualization.**

![Scheduler Animation](observations\Project_Simulation.gif)
<p align="center"><i>Live simulation of urgent, normal, and low-priority packets being scheduled with preemption</i></p>

---

### Features

- **Preemptive Priority Scheduling** – Urgent packets instantly preempt normal/low ones  
- **Timed Automata Engine** – Formal model with states, clocks, guards, and invariants  
- **Dynamic Deadlines via ML** – Gradient Boosting Regressor predicts per-packet deadlines  
- **Rule-Based + ML Hybrid Classifier** – Combines protocol rules with learned behavior  
- **Real-Time Animated Dashboard** – Beautiful live visualization of queues, states, and packet flow  
- **Comprehensive Analytics** – Waiting times, throughput, preemption count, success rate  
- **Exportable Results** – MP4 animation, PNG plots, detailed text report  

---

### How to Run (VS Code / Local Machine)

#### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/enhanced-packet-scheduler.git
```
---

### Install dependencies and update path
```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib networkx

training_csv = "path/to/your/Midterm_53_group.csv"
simulation_csv = "path/to/your/Midterm_53_group.csv"
```


