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
| **Embedded Linux** | Custom image and boot workflows, application startup, device configuration, and PS–PL integration |
| **Edge AI** | Object detection, segmentation, pose estimation, and deployment of neural-network inference on embedded hardware |
| **AI acceleration** | Vitis AI and DPU-based inference workflows, model integration, and accelerator-aware execution |

## Embedded Vision & Linux Platform Development

Exploring the embedded vision ecosystem on AMD Xilinx Kria platforms, spanning Vitis Vision Library–based image processing, embedded Linux development, kernel and device driver development, and custom platform integration using PetaLinux and Yocto. The focus includes developing vision applications for Kria SOMs, building custom Linux environments, and creating reusable Docker images for application deployment, development, and testing on embedded targets.
Individual projects retain their own implementation details and instructions in their respective repositories.

## Platform & Toolchain

- **Hardware:** AMD Xilinx Kria KV260 and compatible FPGA-based platforms
- **FPGA development:** Vivado, IP Integrator, AXI-based interfaces, programmable logic
- **Embedded software:** Linux, PetaLinux workflows, C/C++, Python
- **AI deployment:** Vitis AI and DPU-based inference workflows

Tool and platform requirements vary by project. Refer to each project's documentation for its supported versions and exact build steps.

