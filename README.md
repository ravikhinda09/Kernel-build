# 🪐 AERO Kernel - OnePlus 13R / Ace 5 (giulia)

<p align="center">
  <a href="https://github.com/ravikhinda09/Kernel-build/actions/workflows/build.yml">
    <img src="https://img.shields.io/github/actions/workflow/status/ravikhinda09/Kernel-build/build.yml?style=flat-square&logo=github-actions&logoColor=white&label=Build%20Status" alt="Build Status">
  </a>
  <a href="https://github.com/KernelSU-Next/KernelSU-Next">
    <img src="https://img.shields.io/badge/KernelSU--Next-Supported-4bc51d?style=flat-square&logo=android&logoColor=white" alt="KernelSU-Next Supported">
  </a>
  <a href="https://gitlab.com/simonpunk/susfs4ksu">
    <img src="https://img.shields.io/badge/SUSFS-Integrated-fe7d37?style=flat-square&logo=linux&logoColor=white" alt="SusFS Integrated">
  </a>
</p>

---

## 📱 Specifications
Available in dual independent variants to ensure perfect system stability.

- **Device:** OnePlus 13R / Ace 5
- **SoC:** Snapdragon 8 Gen 3 (`SM8650`)
- **Kernel Version:** `Linux 6.1.x`
- **Android Support:** Android 16 (GKI Standard)
- **Available Variants:** 1. **OxygenOS Variant** (for Official OnePlus Stock Firmware)
  2. **AOSP Variant** (Strictly optimized for Custom ROMs like LineageOS, derpfest, etc.)

---

## 🚀 Supported Features
* **Dual-Variant Pipeline:** Separate standalone compilation branches for **Official OnePlus OxygenOS** and **AOSP-Based Custom ROMs** to avoid bootloops and binary conflicts.
* **KernelSU-Next:** Latest next-generation virtualization and injection layer.
* **SusFS Patches:** Fully integrated to spoof system configurations and easily bypass strict banking app detections.
* **Baseband-Guard (BBG LSM):** Custom security module injected to regulate baseband paths.
* **BBR Networking:** Google's BBR TCP Congestion Control enabled with FQ scheduling for stable networking.
* **Smart CI Pipeline:** Dual-persistence caching framework (**ThinLTO** + **Ccache Matrix**) to speed up compilation pipelines.

---

## 📥 Installation

> ⚠️ **CRITICAL:** Make sure to download the exact flashable zip that matches your currently running software (OxygenOS or AOSP) to prevent mounting errors!

1. Go to the [Releases](https://github.com/ravikhinda09/Kernel-build/releases) section.
2. Select and download the specific variant zip for your device.
3. Flash via custom recovery (TWRP/OrangeFox) or via kernel managers (Franco/KernelSU App).

---

## 🤝 Credits & Acknowledgments
* [LineageOS Project](https://github.com/LineageOS) - For the clean base kernel structure.
* [KernelSU-Next Team](https://github.com/KernelSU-Next) - For the next-generation virtualization layers.
* [Simonpunk](https://gitlab.com/simonpunk) - For the robust SusFS framework.
* [Baseband-Guard](https://github.com/vc-teahouse/Baseband-guard) - For the security LSM layers.

---
<p align="center">
  <b>Maintained by <a href="https://github.com/ravikhinda09">@ravikhinda09</a></b>
</p>
