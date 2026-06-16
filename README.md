# Autonomous Warehouse Robot

## Overview

The robot’s primary purpose is to perform inspections in a warehouse and navigate the warehouse while avoiding static and dynamic obstacles.

---

## Project Timeline

| Day | Task                                                                                 | Deliverable                 | Date   |
| --- | ------------------------------------------------------------------------------------ | --------------------------- | ------ |
| 1   | Obtain open-source robot model and dependencies                                      | Model imported successfully | Jun 16 |
| 2   | Verify URDF/Xacro, TF tree, wheel joints                                             | Robot structure validated   | Jun 17 |
| 3   | Test robot mobility in Gazebo; MoveIt integration                                    | Mobile robot operational    | Jun 18 |
| 4   | Configure LiDAR                                                                      | LiDAR scans available       | Jun 19 |
| 5   | Configure IMU                                                                        | IMU data available          | Jun 20 |
| 6   | Configure Camera                                                                     | Camera stream available     | Jun 21 |
| 7   | Import warehouse environment                                                         | Simulation world ready      | Jun 22 |
| 8   | Spawn robot in warehouse and validate sensors                                        | Full simulation setup       | Jun 23 |
| 9   | SLAM implementation                                                                  | Map generation begins       | Jun 24 |
| 10  | SLAM tuning and map generation                                                       | Final warehouse map         | Jun 25 |
| 11  | EKF sensor fusion                                                                    | Stable state estimation     | Jun 26 |
| 12  | Localization (AMCL/Nav2)                                                             | Accurate pose estimation    | Jun 27 |
| 13  | Global Planner (A*)                                                                  | Path generation             | Jun 28 |
| 14  | Dijkstra benchmarking and comparison                                                 | Planner evaluation report   | Jun 29 |
| 15  | Local Planner integration                                                            | Dynamic navigation          | Jun 30 |
| 16  | Controller tuning (PID/Nav2 controllers); Programming sensors for obstacle avoidance | Smooth movement             | Jul 01 |
| 17  | Obstacle avoidance testing                                                           | Safe navigation             | Jul 02 |
| 18  | Shelf navigation missions                                                            | Aisle traversal             | Jul 03 |
| 19  | Charging dock return behavior                                                        | Autonomous docking          | Jul 04 |
| 20  | Full system integration and testing                                                  | End-to-end demo             | Jul 05 |

---

## Development Flow

```text
Obtain Open-Source Robot Model
        ↓
Verify URDF/Xacro & TF Tree
        ↓
Robot Mobility Validation
        ↓
MoveIt Integration
        ↓
LiDAR Configuration
        ↓
IMU Configuration
        ↓
Camera Configuration
        ↓
Warehouse Environment Import
        ↓
Sensor Validation
        ↓
SLAM Mapping
        ↓
Map Tuning
        ↓
EKF Sensor Fusion
        ↓
Localization (AMCL/Nav2)
        ↓
Global Planning (A*)
        ↓
Dijkstra Benchmarking
        ↓
Local Planning
        ↓
Controller Tuning
        ↓
Obstacle Avoidance
        ↓
Shelf Navigation
        ↓
Charging Dock Return
        ↓
Full System Integration & Testing
```

---

## Key Components

### Sensors

* LiDAR
* IMU
* Camera

### Navigation

* SLAM
* AMCL / Nav2
* Global Planner (A*)
* Dijkstra Algorithm
* Local Planner

### Control

* PID Controller
* EKF Sensor Fusion

### Warehouse Tasks

* Obstacle Avoidance
* Shelf Navigation
* Autonomous Docking
* Warehouse Inspection

---

## Final Goal

Develop an autonomous warehouse robot capable of:

* Inspecting warehouse environments
* Building and using maps for navigation
* Avoiding static and dynamic obstacles
* Navigating shelves and aisles
* Returning autonomously to the charging dock
* Performing complete warehouse missions with minimal human intervention.
