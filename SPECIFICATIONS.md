# NVIDIA AI Aerial Specifications (Draft)

This file tracks environment, SDKs, and resources used for experiments
with NVIDIA AI Aerial / 6G Developer Program.

---

## Program Access

- Program: NVIDIA AI Aerial / 6G Developer Program
- Access Level: Limited / Self-guided using public NGC and GitHub resources

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
