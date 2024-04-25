# Shortest-Metro-Trip

This program utilizes Depth-First Search (DFS) and Breadth-First Search (BFS) algorithms to efficiently find the shortest route between two points on a map. This tool can help you discover the metro system's most direct path from one landmark to another.

## How to Install

1. **Clone the repository:**
    ```bash
    git clone https://github.com/RECodeVault/Shortest-Metro-Trip.git
    ```

2. **Navigate to the project directory:**
    ```bash
    cd Shortest-Metro-Trip
    ```

3. **Start the application:**
    ```bash
    python main.py
    ```

## How to use:
1. You will get prompted with a list of landmarks to start from, and then a list of landmarks to travel to.
2. Once both start and end points are chosen you will receive the shortest route to the chosen destination by metro.
3. You then get an option to alter the start point, end point, or both, and the program will update the information as needed.
4. If you choose to exit, the program will exit with a goodbye message.

# Extra information about DFS and BFS and how they work:

## What is DFS?

Depth-First Search (DFS) is a graph traversal algorithm used to explore and analyze graphs or trees. It starts at a designated "root" node and explores as far as possible along each branch before backtracking.

### DFS, what is it good for:

1. Graph Traversal: It's effective for exploring and visiting all nodes in a graph or tree.
2. Pathfinding: DFS can be adapted to find paths between nodes, including the shortest path in certain scenarios.
3. Cycle Detection: It can detect cycles within a graph, where a cycle is a path that starts and ends at the same node.
4. Maze Solving: DFS is commonly used to solve mazes by exploring paths until the exit is found.

### Steps of DFS:

1. DFS begins at a selected starting node.
2. It explores as far as possible along each branch before backtracking.
3. If a dead end is reached or all adjacent nodes have been visited, it backtracks to the most recent node with unexplored options.
4. DFS traverses the entire graph, ensuring that all reachable nodes are visited.

### Example of DFS:
![DFS diagram](https://www.interviewbit.com/blog/wp-content/uploads/2021/12/DFS-Algorithm-800x620.png)


## What is BFS?

Breadth-First Search (BFS) is another graph traversal algorithm used to explore and analyze graphs or trees. Unlike DFS, which explores as far as possible along each branch before backtracking, BFS explores all nodes at the current depth before moving to the next level.

### BFS, what is it good for:

1. Shortest Path: BFS is ideal for finding the shortest path between two nodes in an unweighted graph. Because it explores nodes level by level, the first time a target node is reached, it guarantees that     the shortest path to that node has been found.
2. Web Crawling: BFS is used in web crawling algorithms to systematically explore and index web pages, starting from a given URL.
3. Network Broadcasting: BFS can be employed in network algorithms to broadcast information efficiently to all nodes in a network.
4. Puzzle Solving: BFS is commonly used to solve puzzles, such as the shortest path in a maze.

### Steps of BFS:

1. BFS begins at a selected starting node.
2. It explores all neighbor nodes at the current depth level before moving to the next depth level.
3. BFS systematically explores nodes level by level, ensuring that nodes closer to the starting point are visited first.
4. BFS typically uses a queue data structure to keep track of the nodes to be explored, ensuring that nodes are visited in the order they were discovered.
5. BFS traverses the entire graph, ensuring that all reachable nodes are visited.

### Example of BFS:
![BFS diagram](https://cdn.hackr.io/uploads/posts/attachments/41Y3Tl3kaPqGDVBPKFjJ1dYYrA33iss48iMklm7h.png)
