# 🖥️ CPU Scheduling Simulator (C++)

## 📌 Overview
This project is a CPU Scheduling Simulator implemented in C++, designed to demonstrate and compare different CPU scheduling algorithms used in operating systems.

It allows users to input process details and simulate how different scheduling strategies handle process execution.

---

## 🚀 Features
- Simulates multiple CPU scheduling algorithms
- Calculates:
  - Waiting Time
  - Turnaround Time
  - Completion Time
- User-friendly input via console
- Displays results in tabular format
- Helps understand OS concepts practically

---

## ⚙️ Scheduling Algorithms Implemented
- First Come First Serve (FCFS)
- Shortest Job First (SJF)  
- Round Robin (RR)
- Priority Scheduling  

---

## 🧠 Concepts Used
- Operating System Scheduling
- Data Structures (Arrays, Queues, Vectors)
- Greedy Algorithms
- Time Complexity Handling

---

## 📂 Project Structure
CPU-Scheduling-Simulator/
│
├── main.cpp
├── parser.h
└── README.md

---

## 🛠️ How to Run

### Step 1: Compile the Code
g++ main.cpp -o scheduler

### Step 2: Run the Program
./scheduler

---

## 🧾 Input Format
- Number of processes
- Arrival time of each process
- Burst time of each process
- Priority (if applicable)
- Time quantum (for Round Robin)

---

## 📊 Sample Output
Process  AT  BT  CT  TAT  WT
P1       0   5   5   5    0
P2       1   3   8   7    4

---

## 🎯 Objective
This project helps in:
- Understanding how CPU scheduling works
- Comparing efficiency of different algorithms
- Practicing C++ and problem-solving skills

---

## 🔧 Future Improvements
- Add GUI (using Qt or other frameworks)
- Visual timeline (Gantt Chart)
- File input/output support
- More advanced algorithms (Multilevel Queue, etc.)

---

## 👨‍💻 Author
- Ashish kumar singh

---

## 📜 License
This project is open-source and free to use for educational purposes.
