Smart Traffic Route Optimization System
An interactive Streamlit-based web application that simulates real-time traffic conditions and finds the most efficient routes using advanced graph algorithms.

Project Overview
This project focuses on solving real-world traffic routing problems using Artificial Intelligence and Graph Theory. It dynamically adjusts road weights based on traffic conditions and computes optimal routes between locations in Nagpur city.

The system also provides visualization on maps and compares multiple algorithms for performance analysis.

Key Features
Multiple Routing Algorithms
Dijkstra (Optimal)
A Star Search (Fast and Optimal)
Greedy Best First Search
AO Star Algorithm (Advanced)

Interactive Map Visualization
Built with Folium
Displays routes, nodes, and traffic conditions

Dynamic Traffic Simulation
Simulates real-time traffic (Low, Medium, High)
Adjustable traffic sensitivity

Custom Location Support
Add new locations using GPS coordinates
Automatically connects to nearest nodes

multi Stop Routing (TSP Mode)
Supports multiple waypoints
Uses Nearest Neighbor approach

Algorithm Performance Comparison
Execution Time
Nodes Explored
Path Cost
Technologies Used
Python
Streamlit
NetworkX
Folium
OSRM API
Requests
Polyline
Project Structure

Smart-Traffic-Optimizer
│── app.py
│── README.md
Installation
Clone the Repository

git clone https://github.com/your-username/smart-traffic-optimizer.git
cd smart-traffic-optimizer
Install Required Libraries

pip install streamlit networkx folium requests polyline
Run the Application

streamlit run app.py
How to Use
Select Source and Destination
Choose Traffic Mode and Algorithm
Optional: Enable multi-stop mode or add custom locations
Click Find Optimal Route
Algorithms Explanation
Dijkstra
Finds shortest path using weighted graph
Optimal
A Star
Uses heuristic (Euclidean distance)
Optimal
Greedy Best First Search
Fast but not always optimal
Not Guaranteed
AO Star
Works on AND-OR graphs
Optimal
Output Includes
Best Route Path
Total Cost
Execution Time
Nodes Explored
Interactive Map with Traffic Visualization
Map Visualization
Low Traffic shown in Green
Medium Traffic shown in Orange
High Traffic shown in Red
Optimal Route shown in Blue
Future Enhancements
Integration with real-time traffic APIs
Machine Learning for traffic prediction
Mobile-friendly UI
Live GPS tracking