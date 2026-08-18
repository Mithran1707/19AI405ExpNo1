<h1>ExpNo 1 :Developing AI Agent with PEAS Description</h1>
<h3>Name: Mithran  A </h3>
<h3>Register Number: 212225220064</h3>


# Vacuum Cleaner Agent

## Aim
To design and implement a simple Vacuum Cleaner Agent using Artificial Intelligence principles and evaluate its performance using the PEAS model.

---

## Theory
A vacuum cleaner agent is an intelligent agent that cleans dirty areas in its environment. The environment consists of rooms or floor locations, where each location may be clean or dirty. The agent uses sensors to detect dirt, obstacles, its current location, and battery level. Based on the sensor inputs, it decides whether to clean the current location or move to another location. If dirt is detected, the agent activates its vacuum mechanism to clean the area; otherwise, it moves to the next location. The performance of the agent is measured by increasing the performance score for every successfully cleaned location and decreasing it for every unnecessary movement or energy consumption. Thus, the vacuum cleaner agent aims to maximize cleanliness while minimizing movement and energy usage.

---

## PEAS Description

| Agent Type | Performance | Environment | Actuators | Sensors |
|------------|-------------|-------------|-----------|---------|
| Vacuum Cleaner Agent | Cleanliness of rooms, minimum time, minimum energy consumption | Rooms, floor, dirt, obstacles | Move (left, right, forward, backward), suck dirt, turn on/off | Dirt sensor, location sensor, obstacle sensor, battery level sensor |

---

## Design Steps

### Step 1: Identifying the Input
- Dirt status of the current location
- Current location
- Obstacle detection
- Battery level

### Step 2: Identifying the Output
- Move to the required location and clean the dirty area using the vacuum.

### Step 3: Developing the PEAS Description
PEAS description is developed by defining the performance measure, environment, actuators, and sensors of the vacuum cleaner agent.

### Step 4: Implementing the AI Agent
