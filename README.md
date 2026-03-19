# GLidE-SLAM
GL-Accelerated Indirect-Direct Embedded SLAM

With the growing demand for robotics, au-
tonomous drones, and wearable extended reality systems, the
deployment of Visual SLAM on embedded devices remains
challenging. Tracking must sustain high frame rates while
preserving compute resources for map extension and mainte-
nance. This paper presents GLidE-SLAM, a monocular hybrid
indirect-direct framework that addresses this by architectural
separation: the system performs GPU-accelerated direct pho-
tometric tracking on intermediate frames, while reserving the
full indirect pipeline for keyframes when map extension and
global consistency are required. We leverage highly parallel
photometric operations for pose-only estimation without depth
optimization or map point creation, making the workload
suitable for GPU offloading and freeing CPU resources for
backend tasks. We implement the direct tracker using vendor-
agnostic OpenGL ES 3.1 compute shaders rather than CUDA,
enabling deployment across commodity embedded platforms.
To our knowledge, this is the first complete direct photometric
pose estimator realized via compute shaders for embedded-class
devices. Experiments on target platforms demonstrate over 2×
higher frame rates than the CPU-only baseline while main-
taining trajectory accuracy, improving practical deployment on
resource-constrained hardware.
