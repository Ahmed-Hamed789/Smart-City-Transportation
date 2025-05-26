# Smart City: Cairo Transportation Optimization 🏙️

An interactive Streamlit application for optimizing Cairo's transportation network using various algorithms and data structures.

## Features

- 🗺️ **Interactive Network Map**
  - Visualize the entire transportation network
  - Display shortest paths and minimum spanning trees
  - Highlight critical facilities and high-population areas

- 🛣️ **Route Planning**
  - Standard routing using Dijkstra's algorithm
  - Emergency routing using A* algorithm
  - Time-dependent path optimization

- 🌉 **Network Design**
  - Minimum Spanning Tree (MST) using Kruskal's algorithm
  - Optimization for existing and potential new roads
  - Priority-based network expansion

- 🚍 **Public Transport**
  - Dynamic programming for bus allocation
  - Metro line optimization
  - Demand-based route planning

- 🚦 **Traffic Management**
  - Greedy algorithm for traffic signal optimization
  - Intersection priority calculation
  - Critical node identification

## Installation

```bash
# Clone the repository
git clone https://github.com/Ahmed-Hamed789/Smart-City-Transportation.git

# Navigate to project directory
cd Smart-City-Transportation

# Install required packages
pip install -r requirements.txt
```

## Requirements

```
streamlit
networkx
matplotlib
pandas
numpy
```

## Usage

```bash
# Run the Streamlit app
streamlit run main.py
```

## Data Structure

The application uses various data structures:
- Graphs for network representation
- Priority queues for pathfinding
- Disjoint Set Union for MST
- Dynamic programming tables for optimization
- Adjacency lists for network traversal

## Algorithms

1. **Kruskal's Algorithm**
   - Used for minimum spanning tree
   - Optimizes network connectivity
   - Considers construction and maintenance costs

2. **Dijkstra's Algorithm**
   - Standard route planning
   - Time-dependent edge weights
   - Multiple optimization criteria

3. **A* Algorithm**
   - Emergency route planning
   - Heuristic-based pathfinding
   - Priority routing for critical facilities

4. **Dynamic Programming**
   - Public transport optimization
   - Bus route allocation
   - Resource distribution

5. **Greedy Algorithm**
   - Traffic signal optimization
   - Intersection priority assignment
   - Real-time traffic management



## Acknowledgments

- Data provided by Cairo Transportation Authority
- Streamlit for the interactive web interface
- NetworkX for graph algorithms
- Matplotlib for visualization
