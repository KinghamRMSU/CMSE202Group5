# CMSE202 Group 5: Optimize Delivery Route Planning for a Business  
**Focus:** Graph Theory & Agent-Based Modeling (ABM)  
**Group Members:** Quinn Brennan, Rebecca Kingham, Itiel Castro, Yunxin Lu, Peiyin Yang

---

## Introduction
Our final project for CMSE202 optimizes techniques for delivery route planning by using graph theory and ABM. In this project, we first model a city (East Lansing in this project) as a graph, where intersections are nodes and streets are edges. Then we compute the optimal route with several stops for agents to minimize delivery distance and time. Instead of creating a new graph, we use Google Maps API in this simulation.

---

## Features
- **Libraries:**  
  - `googlemaps`
  - `networkx` 
  - `matplotlib`
    
- **City Modeling:**
  - **Nodes:** Intersections 
  - **Edges:** Streets
  - **City:** East Lansing, about 2.891 mi^2. 
    
- **Simulation:**
  - Incorporate actual distance and travel time data in the Google Maps Distance API with agent-based simulation. This simulation models the optimal delivery route.


