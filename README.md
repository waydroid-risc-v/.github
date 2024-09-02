# Waydroid on RISC-V

## Introduction

This project aims to get Waydroid running on RISC-V, still WIP. And you can get system.img & vendor.img [here](https://github.com/waydroid-risc-v/waydroid/releases/tag/0.0.1-alpha).

Ideally it can work on every RISC-V Linux using desktop environment with Wayland support.

## Status

### 2024/09/02: 

* LineageOS 17.1 (Android 10) images has been successfully built.

* It can boot into home launcher on MilkV Jupiter(SpaceMiT X60, Ubuntu 23.10) , but still buggy.

* And it's extremely slow because we are using on software renderer now (LLVMPIPE in Mesa3D)

![screenshot](https://github.com/user-attachments/assets/fff43e2a-2478-4346-9fd8-7129f575af83)

## Related Links

[RISC-V Android Repo](https://github.com/riscv-android-src). Our project is based on their effort trying to get Android 10 running on RISC-V.

[llvmpipe: add a new JIT engine based on LLVM ORCJIT, also add RISC-V support](https://gitlab.freedesktop.org/mesa/mesa/-/merge_requests/26018). Our project apply those patches from Yukari Chiba [uploaded here](https://github.com/YukariChiba/deepin-mesa/commit/8d5e7c317493d459948e8cf6f29110e39f823ca0)

[RISC-V Android SIG](https://lists.riscv.org/g/sig-android)

[Waydroid](https://waydro.id/)
