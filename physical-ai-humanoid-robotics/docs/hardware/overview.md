# Hardware Requirements Overview

This course is technically demanding. It sits at the intersection of three heavy computational loads: Physics Simulation (Isaac Sim/Gazebo), Visual Perception (SLAM/Computer Vision), and Generative AI (LLMs/VLA).

Because the capstone involves a "Simulated Humanoid," the primary investment must be in High-Performance Workstations. However, to fulfill the "Physical AI" promise, you also need Edge Computing Kits (brains without bodies) or specific robot hardware.

Building a "Physical AI" lab is a significant investment. You will have to choose between building a physical On-Premise Lab at Home (High CapEx) versus running a Cloud-Native Lab (High OpEx).

### Summary of Architecture

To teach this successfully, your lab infrastructure should look like this:

| Component        | Hardware                   | Function                                                               |
| ---------------- | -------------------------- | ---------------------------------------------------------------------- |
| **Sim Rig**      | PC with RTX 4080+ & Ubuntu 22.04 | Runs Isaac Sim, Gazebo, Unity, and trains LLM/VLA models.              |
| **Edge Brain**   | Jetson Orin Nano           | Runs the "Inference" stack. Students deploy their code here.           |
| **Sensors**      | RealSense Camera + Lidar   | Connected to the Jetson to feed real-world data to the AI.             |
| **Actuator**     | Unitree Go2 or G1 (Shared) | Receives motor commands from the Jetson.                               |
