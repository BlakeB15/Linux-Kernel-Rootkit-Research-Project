# Linux-Kernel-Rootkit-Research-Project

Overview

This project explores Linux kernel rootkit techniques in a controlled lab environment to better understand kernel attack surfaces, stealth persistence methods, and defensive detection strategies.

The goal of this research is educational and defensive: to study how kernel-level threats operate and how they can be detected and mitigated.


Objectives

Understand Linux kernel module (LKM) behavior and internals, Explore kernel-level hooking and monitoring techniques, Analyze stealth persistence and privilege abuse mechanisms, Evaluate modern kernel protections and detection methods, Document defensive strategies and indicators of compromise

Features

Loadable Kernel Module (LKM) implementation, Kernel function hooking for filesystem event monitoring, Logging of privileged operations and directory creation activity, Investigation of kernel symbol resolution techniques, Documentation of detection and mitigation strategies

Ethical & Legal Notice

This project was developed strictly for:

educational purposes, defensive security research
controlled lab environments
Do NOT deploy or use these techniques on systems you do not own or have explicit permission to test.

Lab Environment

OS: Ubuntu Linux (tested on kernel 5.x+)
Virtualization: VirtualBox / VMware
Architecture: x86_64
Development Tools: GCC, Make, Linux kernel headers
Note: Modern kernels include protections that may prevent certain hooking techniques. This project explores these protections and their implications.

## References

- Xcellerator. "Linux Rootkits: New Methods for Kernel Hooking." 2020.  
  https://xcellerator.github.io/posts/linux_rootkits/

