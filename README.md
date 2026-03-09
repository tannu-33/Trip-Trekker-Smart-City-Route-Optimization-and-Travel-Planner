TripTrekker is a C++ based city travel optimization system that helps users plan efficient travel routes across districts while considering distance, traffic conditions, and travel time. The system integrates multiple Data Structures and Algorithms (DSA) concepts such as Graph algorithms, Traveling Salesman Problem (TSP), Greedy scheduling, and Depth First Search to generate optimal travel plans.

The application allows users to:

Plan a full city tour

Find the shortest path between districts

Determine the fastest route considering traffic

Check current traffic conditions

Generate a daily activity schedule

This project demonstrates the practical use of graph algorithms and optimization techniques in real-world route planning problems.

Features
1. Full City Tour Optimization

Calculates the most efficient way to travel across all districts using the Traveling Salesman Problem (TSP) algorithm.

2. Shortest Distance Finder

Uses Dijkstra’s Algorithm to compute the shortest distance between any two districts.

3. Fastest Path Finder

Uses Depth First Search (DFS) to explore all possible routes between two districts and determines the fastest route based on traffic and travel time.

4. Traffic Simulation

Traffic conditions are randomly simulated (LOW, NORMAL, HIGH), affecting travel time dynamically.

5. Dynamic Speed Adjustment

Users can update travel speed to see how it impacts route time calculations.

6. Full Day Activity Planner

Uses the Greedy Activity Selection Algorithm to schedule the maximum number of activities in a day without time conflicts.

7. District Travel Information

Displays:

Distance between districts

Current traffic condition

Estimated travel time

Algorithms Used

The project integrates several fundamental algorithms:

Algorithm	Purpose
Dijkstra’s Algorithm	Shortest distance between two districts
Depth First Search (DFS)	Finding all possible paths
Traveling Salesman Problem (Branch & Bound)	Minimum distance city tour
Permutation-based TSP	Minimum time tour planning
Greedy Activity Selection	Optimal day activity scheduling
QuickSort	Sorting activities based on end time
Data Structures Used

Graph (Adjacency Matrix)

Arrays

Vectors

Structures

Recursion

How the System Works

The city is modeled as a graph of 11 districts, where:

Vertices represent districts

Edges represent roads between districts

Each edge stores:

Distance

Traffic condition

Estimated travel time

Traffic conditions dynamically affect travel time using the formula:

Time = Distance / Speed

Traffic impact:

LOW traffic → faster travel

NORMAL traffic → standard speed

HIGH traffic → reduced speed

Menu Options

When the program runs, users can choose from the following options:

1. Plan a full city tour
2. Update speed
3. View current traffic conditions
4. Shortest distance between districts
5. Minimum distance to travel entire city
6. Fastest path between districts
7. Full day activity planner
8. Exit
