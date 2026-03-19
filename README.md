# GLidE-SLAM: GL-Accelerated Indirect-Direct Embedded SLAM

**Paper submitted to IROS 2026 (under review)**

## 🚀 CODE COMING SOON

Full implementation will be released publicly upon acceptance.

## Overview

GLidE-SLAM is a monocular hybrid Visual SLAM framework for embedded devices. The system achieves **over 2× higher frame rates** than CPU-only baseline while maintaining trajectory accuracy by:

- GPU-accelerated direct photometric tracking on intermediate frames
- Vendor-agnostic OpenGL ES 3.1 compute shaders (not CUDA)
- Efficient CPU-GPU workload separation

**First complete direct photometric pose estimator via compute shaders for embedded devices.**

## Video Teaser

🎥 **[Watch on YouTube](https://youtu.be/RgCVw1D7rwg)**

## Target Platforms

- Autonomous robots and drones
- Wearable AR/VR systems
- Multi-robot systems
- Commodity embedded hardware (tested on Radxa Zero 3W, AMD Radeon 890M)

---

**License**: TBD upon code release  
**Citation**: Available upon acceptance
