# High OpEx: The "Ether" Lab (Cloud-Native)

This option is best for rapid deployment or for students with laptops that do not meet the workstation requirements.

**Warning on Latency:** Simulating in the cloud works well, but controlling a real robot from a cloud instance is dangerous due to latency. The recommended solution is for students to train their models in the cloud, download the trained model (weights), and then flash it to a local Jetson kit for controlling a physical robot.

## 1. Cloud Workstations (AWS/Azure)
Instead of buying physical PCs, you rent instances from a cloud provider.

-   **Instance Type**: AWS g5.2xlarge (A10G GPU, 24GB VRAM) or g6e.xlarge.
-   **Software**: NVIDIA Isaac Sim on Omniverse Cloud (requires specific AMI).
-   **Cost Calculation**:
    -   Instance cost: ~$1.50/hour (spot/on-demand mix).
    -   Usage: 10 hours/week × 12 weeks = 120 hours.
    -   Storage (EBS volumes for saving environments): ~$25/quarter.
    -   **Total Cloud Bill: ~$205 per quarter.**

## 2. Local "Bridge" Hardware
You cannot eliminate hardware entirely for "Physical AI." You still need the edge devices to physically deploy the code.

-   **Edge AI Kits**: You still need the [Economy Jetson Student Kit](./edge-kit.md).
    -   **Cost**: $700 (One-time purchase).
-   **Robot**: You still need one physical robot for the final demo.
    -   **Cost**: $3,000 (Unitree Go2 Standard).
