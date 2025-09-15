# Yocto-Quick-Build

This repository documents my learning journey with the **Yocto Project**.  
The first step was completing the official [Quick Build Guide](https://docs.yoctoproject.org/5.0.12/brief-yoctoprojectqs/index.html).

## 🛠️ Steps Followed
1. Cloned `poky` repository, branch `scarthgap`.
2. Set up environment with `oe-init-build-env ../builds/QuickBuild/`.
3. Ran `bitbake core-image-sato`.
4. Booted the image in **QEMU**.

## 📂 Outputs
- Successfully built **core-image-sato** (~few hours build).
- Booted into a graphical environment inside QEMU.

  <img width="1531" height="428" alt="Screenshot 2025-09-15 110801" src="https://github.com/user-attachments/assets/00e1f5d6-1fd4-4862-ac36-44580b5579c1" />
