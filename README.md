# LAB1 - Embedded Linux System Setup

## 1. Overview

This project focuses on building and running an Embedded Linux system on an ARM-based virtual platform.

## 2. Objectives

- Understand the Embedded Linux boot process.
- Build and configure the Linux kernel.
- Learn about U-Boot bootloader.
- Create a root filesystem using BusyBox.
- Run Embedded Linux using QEMU.

## 3. Technologies Used

- Operating System: Ubuntu Linux
- Architecture: ARMv7
- Linux Kernel: 5.15
- Bootloader: U-Boot
- Emulator: QEMU
- Root Filesystem: BusyBox
- Programming Language: C

## 4. Project Components

- Linux kernel configuration and build
- U-Boot bootloader
- ARM device tree
- Root filesystem
- QEMU virtual machine

## 5. Build and Run

The project was developed and tested on Ubuntu Linux.

Example QEMU command:

```bash
qemu-system-arm \
  -M vexpress-a9 \
  -cpu cortex-a9 \
  -m 512M \
  -nographic \
  -kernel ~/embedded_lab1/output/u-boot
```

Note: The command above is an example from the development environment. The exact boot command depends on the configured boot flow and generated images.

## 6. Learning Outcomes

- Understand the Linux boot process.
- Learn how to configure and build an ARM Linux kernel.
- Understand the relationship between the bootloader, kernel, device tree, and root filesystem.
- Practice running an Embedded Linux system in QEMU.

## 7. Author

**Name:** Le Minh Dang  
**University:** FPT University (FPTU)

## 8. Status

Completed coursework and practical experiments. The repository documents the project configuration, source files, and testing results.
