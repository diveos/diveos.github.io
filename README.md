# Dive OS
Dive OS is an open source operating system focused on simplicity and speed developed by [Jeron Aldaron Lau](https://github.com/OxyDeadbeef).  There are two parts to Dive OS: the user interface and the kernel.

## User Interface
The user interface is called `dive`.  You can find it at [diveos.github.io/dive](https://diveos.github.io/dive).  The `dive` desktop environment interface should be able to run as a program on any other OS.

## Kernel
The kernel is based on the Linux kernel, with a few modifications.  They are as follows:
* Mod kernel to run applications using realtime algorithm to reduce latency as much as possible even if it makes things slightly slower (This code already exists, luckily).
* Remove obsolete and ancient APIs from kernel to improve security.
* Re-write some of the kernel in Rust for safety guarantees, eventually all of it.
