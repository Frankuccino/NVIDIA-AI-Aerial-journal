# NVIDIA AI Aerial Specifications (Draft)

This file tracks environment, SDKs, and resources used for experiments
with NVIDIA AI Aerial / 6G Developer Program.

---

## Program Access

- **Program**: NVIDIA 6G Developer Program / AI Aerial
- **Role**: Partner
- **NGC Access**: Full access to the [NGC Catalog](https://catalog.ngc.nvidia.com/), including downloading and deploying AI Aerial containers, SDKs, and datasets.
- **Organization Management**: Can manage your program-specific org and resources on NGC.
- **Software & Tools Access**:
  - **Aerial CUDA-Accelerated RAN**: Full containerized RAN software stack for 6G networks
  - **Aerial Framework**: High-level framework for AI-native 6G network development
  - **Aerial Omniverse™ Digital Twin (AODT)**: Tools to create physically accurate digital twins for simulating and validating 6G networks, including high-speed ray tracing for urban and RF modeling
  - **Sionna Neural Radio Framework**: Open-source library for simulating 6G link-level communications and training AI models using PyTorch/TensorFlow
- **Support & Communication**: Direct access to NVIDIA team via the Aerial Forum; program feedback is welcomed
- **Exclusive Resources**: Specialized technical training, documentation, and collaboration opportunities
- **Main Program Page**: [NVIDIA AI Aerial](https://developer.nvidia.com/industries/telecommunications/ai-aerial)

---

## Tools / SDKs / Resources

| Tool / SDK / Resource          | Version / Notes                                                                       |
| ------------------------------ | ------------------------------------------------------------------------------------- |
| CUDA-Accelerated RAN           | Latest available on NGC / GitHub                                                      |
| Sionna                         | Latest stable                                                                         |
| Aerial Framework               | Latest stable                                                                         |
| NVIDIA GPU-Optimized AMI (AWS) | Marketplace AMI ID: 676eed8d-dcf5-4784-87d7-0de463205c17 (optional / region-specific) |
| AODT Installer                 | Version 1.4.1                                                                         |
| Python                         | 3.11+                                                                                 |
| CUDA Toolkit                   | 12.x (to match AMI / RAN requirements)                                                |

---

## Development Environment

- **OS**: macOS (local) / AWS EC2 (remote GPU)
- **Editor / IDE**: VSCode
- **Terminal / Shell**: iTerm2 (zsh)

---

## Notes

- Repository focuses on **documentation, lessons, and experiments**.
- Original NVIDIA code or datasets may not be included due to licensing.
- SPECIFICATIONS.md will be updated as access and environment details evolve.
