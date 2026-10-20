<div align="center">

# Kria Vision AI

### Embedded Vision · FPGA Acceleration · Embedded Linux · Edge AI

Engineering embedded vision systems on AMD Xilinx Kria platforms from video pipelines to Linux-based deployment and accelerated computer vision.

<img width="1198" height="733" alt="image" src="https://github.com/user-attachments/assets/d5938159-f1b2-452b-beec-1ceff839a011" />


</div>

---

## Overview

**Kria Vision AI** is a hands-on engineering workspace for exploring how embedded vision systems are designed, integrated, and deployed on AMD Xilinx Kria platforms.

The work spans the boundary between hardware and software: building video paths in programmable logic, controlling hardware from the processing system, bringing up Linux-based applications, and evaluating AI inference on edge devices. The emphasis is on understanding the complete system—not just the model, but also the interfaces, data movement, boot flow, runtime, and debugging required to make it work.

## Engineering Focus

| Area | What it covers |
| --- | --- |
| **Embedded vision** | Video timing, pixel streams, camera and display paths, test-pattern generation, and vision pipeline integration |
| **FPGA design** | Vivado IP integration, AXI interfaces, programmable-logic data paths, and hardware–software co-design |
| **Embedded Linux** | Custom image and boot workflows, application startup, device configuration, and PS–PL integration |
| **Edge AI** | Object detection, segmentation, pose estimation, and deployment of neural-network inference on embedded hardware |
| **AI acceleration** | Vitis AI and DPU-based inference workflows, model integration, and accelerator-aware execution |
| **Profiling and validation** | Functional debugging, inference profiling, system bottleneck analysis, and performance-oriented experimentation |

## Project Directions

The repository brings together work across several related directions:

- **Video pipeline development** — establishing and validating video generation, timing, streaming, and display output on the Kria KV260.
- **Embedded AI inference** — exploring object detection and other vision workloads on Kria hardware.
- **DPU profiling** — examining inference performance and the practical considerations of running accelerated models at the edge.
- **Linux-based deployment** — developing repeatable paths from hardware design and boot configuration to application execution on the target.

Individual projects retain their own implementation details and instructions in their respective repositories.

## Platform & Toolchain

- **Hardware:** AMD Xilinx Kria KV260 and compatible FPGA-based platforms
- **FPGA development:** Vivado, IP Integrator, AXI-based interfaces, programmable logic
- **Embedded software:** Linux, PetaLinux workflows, C/C++, Python
- **AI deployment:** Vitis AI and DPU-based inference workflows
- **Development practices:** Git, hardware bring-up, debugging, profiling, and system integration

Tool and platform requirements vary by project. Refer to each project's documentation for its supported versions and exact build steps.

