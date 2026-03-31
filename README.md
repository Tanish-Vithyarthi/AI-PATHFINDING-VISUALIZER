# AI Pathfinding Visualizer

## Overview
AI Pathfinding Visualizer is an interactive project that demonstrates how Artificial Intelligence algorithms find optimal paths in a grid-based environment.

It allows users to visualize how algorithms explore nodes and determine the shortest path between a start and end point.

---

## Problem Statement
In real-world systems like GPS navigation, finding the shortest path is essential but not easily understood.

This project solves:
How to visualize and understand intelligent pathfinding decisions made by AI systems?

---

## Features
- Interactive grid-based interface  
- User can:
  - Set Start Node
  - Set End Node
  - Add Obstacles (Walls)  
- Real-time algorithm visualization  
- Supports multiple algorithms:
  - Breadth-First Search (BFS)
  - Depth-First Search (DFS)
  - A* (A-Star) Algorithm  
- Path reconstruction after reaching goal  

---

## Controls
- Mouse Click → Place start, end, obstacles  
- 1 → BFS  
- 2 → DFS  
- 3 → A*  
- SPACE → Run Algorithm  
- C → Clear Grid  

---

## Tech Stack
- Language: Python  
- Library: Pygame  
- Concepts Used:
  - AI Search Algorithms  
  - Graph Theory  
  - Heuristics  

---

## Architecture
- Grid-based system (2D matrix)  
- Each cell = Node  
- Works like a graph:
  - Nodes → Grid cells  
  - Edges → Adjacent cells  

Flow:
1. User creates grid  
2. Grid converts to graph  
3. Algorithm runs  
4. Visualization updates in real-time  

---

## Installation

# Clone repository
git clone https://github.com/Harsh-872/AI-Pathfinder-Visualizer.git

# Open folder
cd pathfinding-visualizer

# Install dependencies
pip install pygame

# Run project
python main.py

---

## Testing
- Verified all algorithms  
- Checked:
  - Obstacles handling  
  - Start/End placement  

Edge cases:
- No path available  
- Start = End  

---

## Algorithm Behavior
- BFS → Always shortest path  
- DFS → Not always optimal  
- A* → Fast & optimal  

---

## Future Enhancements
- Add Dijkstra’s Algorithm  
- Weighted nodes (traffic simulation)  
- GUI buttons instead of keyboard  
- Real-world map integration  
- Performance metrics (time, nodes explored)  
- 3D visualization  

---

## Learning Outcomes
- Understanding search algorithms  
- Importance of heuristics  
- Difference between informed and uninformed search  
- Practical AI implementation  

---

## Author
Name: Tanish Paharia  
Course: BTech CSE Core  
Institute: VIT Bhopal  

---

## Final Note
This project demonstrates how AI algorithms solve real-world pathfinding problems in a simple and visual way.
