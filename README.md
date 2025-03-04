

# **AI Agent Maze Navigation - Jupyter Notebook**  

This Jupyter Notebook implements an AI agent that navigates a maze using various search algorithms. The agent starts at a predefined position and explores the environment to find the goal while avoiding obstacles.  

## **Implemented Search Algorithms**  
- **Breadth-First Search (BFS)** – Ensures the shortest path but has high space complexity.  
- **Depth-First Search (DFS)** – Space-efficient but may return suboptimal paths.  
- **Greedy Best-First Search** – Uses heuristics for quick navigation but isn’t always optimal.  
- **A* Search** – Balances optimality and efficiency using cost and heuristic functions.  

## **Features**  
✅ Maze is represented as a 2D grid.  
✅ AI agent dynamically explores paths using selected search algorithms.  
✅ Performance comparison of time complexity, space complexity, and path length.  
✅ Interactive execution with step-by-step visualization of agent movement.  

## **Usage Instructions**  
1. Open the Notebook (`AgentsSolution.ipynb`) in Jupyter Notebook or Google Colab.  
2. Run the initial setup to import dependencies and define the maze.  
3. Choose a search algorithm and execute the respective function.  
4. The notebook will display the agent's path and performance metrics.  

## **Comparison Table**  

| Algorithm                  | Time Complexity         | Space Complexity        | Path Length  |  
|----------------------------|------------------------|-------------------------|--------------|  
| **BFS**                    | O(b^d)                 | O(b^d)                  | Shortest     |  
| **DFS**                    | O(b^d)                 | O(d)                     | Longest      |  
| **Greedy Best-First**       | O(b^m)                 | O(b^m)                   | Varies       |  
| **A* Search**               | O(b^m) (worst case)    | O(b^m)                   | Optimal      |  

## **Conclusion**  
- **BFS** guarantees the shortest path but consumes more memory.  
- **DFS** is memory-efficient but may take longer paths.  
- **Greedy Best-First** is fast but not always optimal.  
- **A* Search** is the best balance between efficiency and optimality.  

This notebook is a great resource for understanding AI pathfinding techniques and evaluating different search algorithms for maze navigation. 🚀  

---

