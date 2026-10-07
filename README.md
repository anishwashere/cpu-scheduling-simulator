# ⚡ CPU Scheduling Simulator

> An interactive web-based simulator for visualizing and comparing classic CPU scheduling algorithms.

**Simulate. Visualize. Compare.**

Built as a CPU scheduling and operating-systems learning tool with an interactive Streamlit interface, scheduling engine, performance metrics, Gantt charts, CSV input, and multi-algorithm comparison.

---

## 🚀 Live Demo

🌐 **Streamlit App:**  
https://cpu-scheduling-simulatorgit-hnpdgxygxweye8k4mbsdgq.streamlit.app/

---

## 📌 Problem Statement

CPU scheduling is a fundamental operating-system concept where the scheduler determines which process should be executed by the CPU and in what order.

Understanding scheduling algorithms can be difficult when working only with static tables and manually calculated examples.

This project provides an interactive simulator where users can:

1. Create or upload a process workload
2. Select a scheduling algorithm
3. Run the simulation
4. Visualize CPU execution using a Gantt chart
5. Analyze scheduling metrics
6. Compare multiple algorithms on the same workload

---

# ✨ Features

### 🧠 Four Scheduling Algorithms

The simulator supports:

- **FCFS — First Come First Serve**
- **SJF — Shortest Job First**
- **Priority Scheduling — Non-preemptive**
- **Round Robin — Preemptive**

Round Robin supports a configurable time quantum.

---

### 📝 Manual Process Input

Processes can be entered directly through the interface.

Each process contains:

| Field | Description |
|---|---|
| PID | Process identifier |
| Arrival Time | Time at which the process enters the ready queue |
| Burst Time | CPU execution time required |
| Priority | Process priority |

Example:

```text
P1 → Arrival: 0, Burst: 5, Priority: 2
P2 → Arrival: 1, Burst: 3, Priority: 1
P3 → Arrival: 2, Burst: 4, Priority: 3
