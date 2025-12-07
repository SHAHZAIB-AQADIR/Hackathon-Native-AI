# The "Digital Twin" Workstation

This is the most critical component, required for each student. NVIDIA Isaac Sim is an Omniverse application that requires "RTX" (Ray Tracing) capabilities. Standard laptops (MacBooks or non-RTX Windows machines) will not work.

### GPU (The Bottleneck)
-   **Required**: NVIDIA RTX 4070 Ti (12GB VRAM) or higher.
    -   **Why**: You need high VRAM to load the USD (Universal Scene Description) assets for the robot and environment, plus run the VLA (Vision-Language-Action) models simultaneously.
-   **Ideal**: RTX 3090 or 4090 (24GB VRAM) allows for smoother "Sim-to-Real" training.

### CPU
-   **Required**: Intel Core i7 (13th Gen+) or AMD Ryzen 9.
    -   **Why**: Physics calculations (Rigid Body Dynamics) in Gazebo/Isaac are CPU-intensive.

### RAM
-   **Required**: 64 GB DDR5 (32 GB is the absolute minimum, but will crash during complex scene rendering).

### Operating System
-   **Required**: Ubuntu 22.04 LTS.
    -   **Note**: While Isaac Sim runs on Windows, ROS 2 (Humble/Iron) is native to Linux. Dual-booting or dedicated Linux machines are mandatory for a friction-free experience.
