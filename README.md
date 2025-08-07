# ChronoQueue - A Linux-Style CPU Scheduler Simulator

A custom-built simulator for core Linux CPU scheduling algorithms including FCFS, SJF, SRTF, Priority, and Round Robin — with both **preemptive** and **non-preemptive** modes.
This project simulates how modern operating systems schedule processes, visualize Gantt charts on a web dashboard, and helps users understand scheduling concepts interactively.

## 🚀 Features

- 🔁 Supports multiple scheduling algorithms:
  - FCFS (First-Come First-Served)
  - SJF (Shortest Job First)
  - SRTF (Shortest Remaining Time First)
  - Priority Scheduling
  - Round Robin

- ⚙️ Preemptive and Non-preemptive modes
- 📊 Gantt Chart generation
- 🌐 Web dashboard for visualizing scheduling in real-time
- ☁️ Deployed on AWS EC2 using a lightweight HTTP server


## 🛠 Tech Stack

- 💻 C++: Core scheduling algorithm implementation  
- 🌐 JavaScript: Visualization logic (converted from C++)  
- 🧱 HTML/CSS: Web dashboard UI  
- ☁️ AWS EC2: Hosting and deployment  
