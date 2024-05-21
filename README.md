# Graph-Transformation-Dijkstra-Python

Determining the Shortest Route, Transforming Graph to Adjacency Matrix and Incidence Matrix using Dijkstra's Algorithm in Python with NetworkX

## Overview

This project demonstrates how to create a graph, transform it into an adjacency matrix and incidence matrix, and find the shortest path using Dijkstra's algorithm. The implementation is done in Python using the NetworkX library.

## Getting Started

### Prerequisites

- Python 3.x
- NetworkX
- Matplotlib

Install the necessary libraries using pip:

```sh
pip install networkx matplotlib
```

### Running the Code

1. Clone the repository:
    ```sh
    git clone https://github.com/whdhdyt21/Graph-Transformation-Dijkstra-Python.git
    cd Graph-Transformation-Dijkstra-Python
    ```

2. Run the `graph.ipynb` notebook in Google Colab or any local Jupyter Notebook environment.

### Features

1. **Shortest Path Calculation**:
   - Use Dijkstra's algorithm to find the shortest path between two nodes.
   
2. **Graph Transformation**:
   - Convert the graph into an adjacency matrix.
   - Convert the graph into an incidence matrix.

3. **Edge Weight Modification**:
   - Modify the weight of an edge in the graph.

4. **Graph Visualization**:
   - Visualize the graph with nodes and edges labeled with distances.

### Usage

The code prompts the user for input to define the graph's nodes and edges along with their distances. After setting up the graph, a menu is displayed to perform various operations:

1. **Find Shortest Path**:
   - Enter the start and end nodes to find the shortest path and distance.
   
2. **Change Edge Weight**:
   - Specify an edge and its new weight to update the graph.
   
3. **Graph Information**:
   - Display the number of nodes and edges in the graph.
   
4. **Display Adjacency Matrix**:
   - Show the adjacency matrix of the graph.
   
5. **Display Incidence Matrix**:
   - Show the incidence matrix of the graph.
   
6. **Exit**:
   - Exit the program.

### Notes

- Ensure you input valid numbers when prompted for nodes, edges, and weights.
- The visualization is generated using Matplotlib and may not display properly in some environments.

## Acknowledgements

- [NetworkX Documentation](https://networkx.github.io/documentation/stable/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)

## Contact

For any issues or inquiries, please open an issue in this repository or contact the maintainer at [your email].

Enjoy exploring graph transformations and shortest path algorithms!
