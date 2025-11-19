# Delivery Route Optimization – Capstone Project (BCA AI & DS)  
**Course:** ENCA351 — Design and Analysis of Algorithms (Lab Assignment 4)  
**Name:** Kartik Singh  
**Semester:** V  

Objective: Logistics Route Optimization using Recurrence, Greedy, DP, Graph Algorithms & TSP

#Overview

This project solves a simplified real-world delivery route optimization problem for an e-commerce logistics system.
A delivery vehicle must:

Start from a warehouse

Deliver parcels to customer locations

Respect delivery time windows

Stay within vehicle capacity

Minimize total distance/time

The assignment integrates multiple algorithmic strategies:

Recurrence relations (route planning logic)

Greedy algorithms (parcel selection using value/weight)

Dynamic Programming (DP) (time-window feasibility)

Graph Algorithms (Dijkstra for shortest path, MST for structure)

TSP brute force/DP (optimal route for small n)

# Input Model

A set of delivery locations including warehouse

A distance matrix (graph)

Parcels with:

value

time window (earliest, latest)

weight

Vehicle weight capacity

# Algorithms Implemented
1. Recurrence Relation

A recursive formulation to compute route cost based on unvisited locations.

2. Greedy Strategy

Select parcels based on value-to-weight ratio until capacity is full.

3. Dynamic Programming

Used to ensure deliveries are feasible within their time windows.

4. Graph Algorithms

-Dijkstra’s Algorithm – shortest path from warehouse to each customer
-Prim’s/Kruskal’s MST – minimal spanning structure for the route network

5. Traveling Salesman Problem (TSP)

Implemented Brute Force and/or Held-Karp DP for small instances (3–6 nodes)

Demonstrates exponential complexity

# Profiling & Visualization

The notebook includes:

Time profiling for TSP on 3, 4, 5, 6 nodes

Memory profiling using memory_profiler

Plots such as:

TSP time vs number of locations

Route visualization (matplotlib/networkx)

Profit vs weight

Delivery window satisfaction
