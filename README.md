# Memory-Management-Visualization

A Python Tkinter-based GUI application for simulating and visualizing memory allocation strategies used in operating systems.

🧐 Overview

Simulates dynamic memory allocation using popular strategies:
First‑Fit – assign process to the first sufficiently large free block
Best‑Fit – choose the smallest possible block that fits
Worst‑Fit – choose the largest available block
Buddy System – repeatedly split blocks in powers of two until the best fit is found
Paging – demonstrate paging by partitioning processes into fixed-size (100 KB) pages

⚙️ Features

Interactive dialog-based input for block and process sizes
Visual text-based display simulating memory block usage
Real-time stats: total memory, used space, fragmentation, efficiency
Controls to allocate, deallocate, reset, and search for processes

🚀 Installation & Usage

Prerequisites
Python 3.x (Tkinter included by default on most systems)
1>Enter number of blocks and processes when prompted
2>Provide sizes for each block and process via dialog
3>Use the GUI buttons to run different allocation strategies
4>Optionally deallocate or search for processes

🛠️ Interactive Functions

Reset Allocations – clears all process assignments
Deallocate Process – remove a specific process by ID
Search Process – locate which block a process is in
Exit – close the application

🎯 Educational Value

Ideal for learning OS concepts:
Observing fragmentation and its impact
Comparing allocation efficiency across strategies
Demonstrating paging behavior in a simple GUI
📎 Licensing

Use and modify as you wish! Please include your preferred LICENSE (e.g., MIT, Apache 2.0).
