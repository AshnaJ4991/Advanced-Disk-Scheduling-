🚀 Advanced Disk Scheduler

This project presents a comprehensive simulation of advanced disk scheduling techniques, aimed at optimizing disk I/O operations. 
It builds upon traditional algorithms like FCFS, SSTF, SCAN, C-SCAN, and LOOK, and introduces priority-based request handling, deadline-aware scheduling, and a simulated machine learning prediction engine for intelligent decision-making.

📚 Project Overview

Modern systems demand faster data retrieval and efficient resource management. 
Traditional disk scheduling approaches, although functional, fall short when dealing with dynamic workloads, priority requests, and real-time deadlines.

This project enhances classic scheduling methods by:
Reducing total seek time.
Improving throughput and system responsiveness.
Handling dynamic, priority-driven, and deadline-sensitive workloads.
Predicting future requests through a basic ML simulation for smarter head movement decisions.

🔥 Features
Implementation of Multiple Scheduling Algorithms:
First Come First Serve (FCFS)
Shortest Seek Time First (SSF)
SCAN (Elevator Algorithm
C-SCAN (Circular SCAN)
LOOK Algorithm

Advanced Enhancements:
Priority-based request servicing.
Deadline-aware task scheduling.
Predictive disk access simulation using request history.
Performance tracking and logging (head movement, seek time).
Flexible sorting options (track number, priority, arrival time).

Technology Stack:
Programming Language: C
Compiler: GCC (GNU Compiler Collection)
Tools: Visual Studio Code, OnlineGDB
Libraries: stdio.h, stdlib.h, string.h, stdbool.h, limits.h

📈 Project Flow
Initialize disk requests with attributes like arrival time, priority, deadline, etc.
Predict the next request using a simple machine learning model.
Select and Execute one of the implemented scheduling algorithms.
Log performance data for comparative analysis.

Output results to console and text files.

🎯 Outcomes
Significant reduction in head movement compared to traditional methods.
Analytical logs for visualizing and comparing algorithm performances.
Base framework for further enhancements using real machine learning models.

🌟 Future Enhancements
Integration of advanced ML models for real-time predictions.
Graphical visualization of disk head movement and performance metrics.
Handling more complex and larger-scale storage scenarios.
Parallel processing support for multi-head disk systems
