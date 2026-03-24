# GLidE-SLAM: GL-Accelerated Indirect-Direct Embedded SLAM

**Paper submitted to IROS 2026 (under review)**

## CODE COMING SOON

Full implementation will be released publicly upon acceptance.

## Overview

GLidE-SLAM is a monocular hybrid Visual SLAM framework for embedded devices. The system achieves **over 2× higher frame rates** compared to CPU-only baseline while maintaining trajectory accuracy by:


- GPU-accelerated direct photometric tracking on intermediate frames
- Vendor-agnostic OpenGL ES 3.1 compute shaders
- Efficient CPU-GPU workload separation
- Tracking offloaded to GPU-> preserves CPU resources for other SLAM modules like mapping and backend processes 

**First complete direct photometric pose estimator via compute shaders for embedded devices (No Cuda).**


https://github.com/user-attachments/assets/55ab743a-a913-476a-bd46-329c49119370



## Target Platforms

- Autonomous robots and drones
- Wearable AR/VR systems
- Multi-robot systems
- Commodity embedded hardware (tested on Radxa Zero 3W, AMD Radeon 890M)

---

**License**: TBD upon code release  
**Citation**: Available upon acceptance
