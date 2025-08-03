# Hospital Pathfinding System using Dijkstra's Algorithm

This Python project demonstrates how to find the shortest path between different locations in a hospital using Dijkstra’s algorithm. It uses `heapq` for priority queue management, `networkx` for graph handling, and `matplotlib` for visualization.

---

## Features

- Add hospital departments as nodes.
- Define routes between them with distances (weights).
- Compute shortest path using Dijkstra’s algorithm.
- Visualize the hospital layout and path using NetworkX and Matplotlib.

---

## Requirements

- Python 3.x
- `networkx`
- `matplotlib`

Install required packages with:

```bash
pip install networkx matplotlib
```

---

## File Structure

```
hospital_pathfinder.py     # Main program with Dijkstra's algorithm and visualization
README.md                  # Project description and instructions
```

---

## Usage

1. **Run the script**:
   ```bash
   python hospital_pathfinder.py
   ```

2. **Expected Output**:
   - Console will display the shortest path between selected hospital locations.
   - A graph will be plotted with:
     - Nodes: Hospital departments
     - Edges: Paths between them
     - Highlighted red path: Shortest path between selected locations

---

## Concepts Used

- **Graph Representation** with custom class
- **Dijkstra’s Algorithm** for shortest path
- **NetworkX & Matplotlib** for graph visualization

---

## Visualization Example

A sample visualization of hospital layout with the shortest path from **Emergency Room** to **ICU**.

---

## Notes

Make sure to fix the following typos in the code:
- Replace `def _init_(self):` with `def __init__(self):`
- Replace `if _name_ == "_main_":` with `if __name__ == "__main__":`

---

###Future Improvements

- GUI for interactive path selection
- Support for one-way paths (directed graph)
- Real-time route updates

---


