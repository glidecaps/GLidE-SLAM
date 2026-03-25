# GLidE-SLAM: GL-Accelerated Indirect-Direct Embedded SLAM

**Paper submitted to IROS 2026 (under review)**

## Overview

GLidE-SLAM is a monocular hybrid Visual SLAM framework for embedded devices. The system achieves **over 2× higher frame rates** compared to CPU-only baseline while maintaining trajectory accuracy.

**We present the First complete direct photometric pose estimator via compute shaders for embedded devices (No Cuda).**

Our framework runs by:

- GPU-accelerated direct photometric tracking on intermediate frames
- Vendor-agnostic OpenGL ES 3.1 compute shaders
- Efficient CPU-GPU workload separation
- Tracking offloaded to GPU-> preserves CPU resources for other SLAM modules like mapping and backend processes 


> **Note:** Results presented reflect parameters at the time of submission: We believe further tuning could yield even higher speedups beyond the reported 2×.

https://github.com/user-attachments/assets/55ab743a-a913-476a-bd46-329c49119370


https://github.com/user-attachments/assets/c5df0884-a663-40c2-8808-c5982aac1b08

Better quality video available: https://youtu.be/Ehjv07Av0AQ


## CODE COMING SOON

To be released upon acceptance.

## Target Platforms — Resource-Constrained Devices:

- Autonomous robots and drones
- Wearable AR/VR systems
- Multi-robot systems
- Commodity embedded hardware (tested on Radxa Zero 3W, AMD Radeon 890M)
- Broader hardware validation across additional embedded platforms is ongoing
---

**License**: TBD upon code release  
**Citation**: Available upon acceptance
