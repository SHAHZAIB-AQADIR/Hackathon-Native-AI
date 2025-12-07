# The "Physical AI" Edge Kit

Since a full humanoid robot is expensive, students learn "Physical AI" by setting up the nervous system on a desk before deploying it to a robot. This kit covers Module 3 (Isaac ROS) and Module 4 (VLA).

### The Brain
-   **Required**: NVIDIA Jetson Orin Nano (8GB) or Orin NX (16GB).
    -   **Role**: This is the industry standard for embodied AI. Students will deploy their ROS 2 nodes here to understand resource constraints vs. their powerful workstations.

### The Eyes (Vision)
-   **Required**: Intel RealSense D435i or D455.
    -   **Role**: Provides RGB (Color) and Depth (Distance) data. Essential for the VSLAM and Perception modules.

### The Inner Ear (Balance)
-   **Required**: Generic USB IMU (BNO055) (Often built into the RealSense D435i or Jetson boards, but a separate module helps teach IMU calibration).

### Voice Interface
-   **Required**: A simple USB Microphone/Speaker array (e.g., ReSpeaker) for the "Voice-to-Action" Whisper integration.

---

## The Economy Jetson Student Kit
Best for: Learning ROS 2, Basic Computer Vision, and Sim-to-Real control.

| Component                     | Model                               | Price (Approx.) | Notes                                                                   |
| ----------------------------- | ----------------------------------- | --------------- | ----------------------------------------------------------------------- |
| **The Brain**                 | NVIDIA Jetson Orin Nano Super Dev Kit (8GB) | $249            | New official MSRP (Price dropped from ~$499). Capable of 40 TOPS.       |
| **The Eyes**                  | Intel RealSense D435i               | $349            | Includes IMU (essential for SLAM). Do not buy the D435 (non-i).         |
| **The Ears**                  | ReSpeaker USB Mic Array v2.0        | $69             | Far-field microphone for voice commands (Module 4).                     |
| **Wi-Fi**                     | (Included in Dev Kit)               | $0              | The new "Super" kit includes the Wi-Fi module pre-installed.            |
| **Power/Misc**                | SD Card (128GB) + Jumper Wires      | $30             | High-endurance microSD card required for the OS.                        |
| **TOTAL**                     |                                     | **~$700 per kit** |                                                                         |
