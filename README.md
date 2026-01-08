# Cruise Control System: PID Disturbance Rejection 🚗
**Tool:** MATLAB / Simulink | **Domain:** Control Theory

## 📌 Project Overview
This project simulates an automatic cruise control system.The goal is to maintain a vehicle speed of **60 km/h** despite external disturbances (such as road hills or friction changes).

## ⚙️ The Challenge
A standard **P-Controller** failed to maintain the target speed.
- **Problem:** Significant steady-state error.
- **Result:** When a disturbance occurred (e.g., a hill), the speed dropped and never recovered to 60 km/h.

## 🛠️ The Solution (PI Controller)
I implemented a **Proportional-Integral (PI) Controller** to eliminate the error.
- **Integral Action:** Continuously sums the error over time to drive the steady-state error to zero.
- **Result:** The system effectively rejects disturbances and maintains the target speed of 60 km/h.

## 📸 System Architecture
![System Model](system_block_diagram.png)

## 📈 Simulation Results (PI Response)
*The graph below shows the PI controller achieving the target speed (Yellow Line) with Zero Steady-State Error.*
![Simulation Graph](pi_response_graph.png)

## 📂 Files Included
- `Cruise_Control.slx`: The complete Simulink model.
- `Presentation.pptx`: Detailed project report and analysis.
