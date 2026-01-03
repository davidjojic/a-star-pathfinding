# Interactive A* Pathfinding Visualizer (C++ / SFML)

Interactive grid-based pathfinding visualizer implemented in **C++ using SFML**.  
Allows drawing walls, selecting start/end points, and visualizing the **A\*** shortest path algorithm in real time.

## Features
- Interactive grid with mouse-based wall drawing
- Start and end point selection
- A* pathfinding on a grid (4-directional movement)
- Real-time visualization of:
  - Open set
  - Closed set
  - Final shortest path

## Controls
- Move cursor: `W A S D`
- Set start point: `Enter` (first press)
- Set end point: `Enter` (second press)
- Draw walls: Hold **Left Mouse Button**
- Start pathfinding: `T`
- Close window: Window close button

## Visualization Legend
- White: Empty cell
- Black: Wall
- Blue: Start
- Yellow: End
- Red: Visited nodes (closed set)
- Green: Frontier (open set)
- Magenta: Final path

## Build & Run
Requires **C++17** and **SFML**.

```bash
g++ main.cpp -o astar -lsfml-graphics -lsfml-window -lsfml-system
./astar
