# Sultan Zumapro KSU Workflow

A high-performance, security-focused kernel for Pixel 9 series (zumapro), merging the stability of **Sultan Kernel** with advanced stealth and networking features.

## 🚀 Key Features
- **Stealth Core:** Integrated **SUSFS** support and **KernelSU** (xxKSU/KowSU variants).
- **Fortress Networking:** Full support for `atp4pixel` suite including BBR v1, IPSet (64k), and XFRM sub-policies.
-**NoMount:** A kernel-based file injection and path redirection framework for Android kernels.
- **Hookless Security:** Option for hookless xxKSU via LSM security hooks (No KProbes).

---

## 📦 Build Variants

| Variant | Description | Base Source |
| :--- | :--- | :--- |
| **KowSU-SUSFS** | Official Sultan base with manual KowSU/SUSFS bridging. | [Official Sultan](https://github.com/kerneltoast/android_kernel_google_tensynos) |
| **xxKSU-NoMount** | Hookless KSU with NoMount. Clean and efficient. | [Official Sultan](https://github.com/kerneltoast/android_kernel_google_tensynos) |

---

## 🤝 Credits & Acknowledgments

This project is made possible thanks to the work of the following developers:

### 🛠️ Kernel & Core Logic
* **[Sultan (kerneltoast)](https://github.com/kerneltoast)** - For the exceptional Sultan Kernel base.
* **[Yapixel](https://github.com/yapixel)** - For kernel patches and specialized configuration logic.

### 🛡️ Stealth & Security
* **[KernelSU Team](https://github.com/tiann/KernelSU)** - For the revolutionary root solution.
* **[KOWX712](https://github.com/KOWX712)** & **[backslashxx](https://github.com/backslashxx)** - For specialized KernelSU integration methods.
* **[maxsteeel](https://github.com/maxsteeel/nomount)** - The creator of **NoMount**.
* **[simonpunk](https://gitlab.com/simonpunk/susfs4ksu)** - The creator of **SUSFS**.

### 🔧 Tools & Distribution
* **[TheWildJames](https://github.com/TheWildJames)** - AnyKernel3 distribution template.
* **[TheSillyOk](https://github.com/TheSillyOk)** - Build automation scripts.
