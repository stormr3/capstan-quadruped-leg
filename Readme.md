# Capstan-Driven Quadruped Leg Mechanism

## Overview
This project explores the design of a capstan drive–based quadruped leg mechanism aimed at achieving smooth, backlash-free joint actuation suitable for legged robotic systems.

## Motivation
Gear-driven joints often introduce backlash, which negatively affects force control and motion smoothness in legged robots. Achieving low-backlash performance using high-precision gear systems is both complex and expensive, making such solutions less accessible for personal and research-oriented projects. Capstan-driven actuation offers a lightweight, low-backlash alternative that enables smoother, more predictable torque transmission and coordinated joint motion, motivating its exploration in robotic mechanisms.

## Current Progress
- Studied capstan mechanics and derived the capstan equation
- Reviewed physical interpretations using pulley and winch analogies
- Analyzed the role of static vs kinetic friction in holding and motion
- Clarified the dynamic nature of tight and loose sides in symmetric systems
- Developed conceptual understanding of capstan mechanics, including tension-based torque transmission and frictional effects during holding and motion
- Designed and modeled a two-drum capstan drive in Fusion 360 with a large radius ratio
- Implemented helical grooves on both drums to guide the cable axially during multiple wraps and prevent lateral slip
- Created a kinematic motion model to visualize input–output rotation
- Modeled a planar five-bar linkage with realistic link dimensions and fully assembled revolute joints
- Verified closed-chain motion and end-effector behavior through manual actuation
- Implemented a concentric base actuation layout to independently drive both five-bar input links in a compact and symmetric configuration


## Next Steps
- Conceptually integrate the capstan-driven actuators with the five-bar linkage inputs
- Observe and document end-effector trajectories for different input motions
