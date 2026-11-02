# Flood-Aware Emergency Routing in Nepal

## Overview
This project explores graph-based emergency route planning under flood-related road disruptions in Nepal. It uses geographic road network data and flood observations to compare pathfinding algorithms and investigate risk-aware routing strategies.

## Objectives
- Represent a road network as a graph.
- Map flood observations to nearby road segments.
- Simulate flood-related road closures.
- Compare BFS, Dijkstra's algorithm, and A* search.
- Implement risk-aware routing using flood exposure.
- Evaluate route distance, execution time, and nodes explored.

## Algorithms
- Breadth-First Search (BFS)
- Dijkstra's Algorithm
- A* Search
- Risk-Aware A* Search

## Technologies Used
- Python
- Google Colab
- NetworkX
- OSMnx
- GeoPandas
- Pandas
- NumPy
- Matplotlib
- Shapely

## Methodology
1. Dataset preparation
2. Road network construction
3. Flood observation mapping
4. Road disruption simulation
5. Route computation
6. Algorithm comparison and evaluation

## Evaluation Metrics
- Route distance
- Flood-exposure proxy
- Number of nodes explored
- Execution time
- Route-finding success rate

## Dataset
The project uses geographic road network data and flood observations for a Nepal-focused case study. Dataset sources, preprocessing steps, and access instructions will be documented separately.

## Limitations
Flood proximity is used as a proxy for potential exposure. A nearby flood observation does not necessarily indicate that a road is flooded, blocked, or unsafe.
