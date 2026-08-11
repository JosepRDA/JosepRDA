# José Araújo

> Embedded systems developer, systems programmer, and CS student.  
> Currently building a bare-metal RTOS for AVR 8-bit from scratch.

---

## What I work with

**Core stack**
- **Languages:** C, C++, Rust, Assembly (x86)
- **Domains:** Embedded systems, OS internals, computer architecture, electronics
- **Graphics:** OpenGL, WebGPU (learning Vulkan next)
- **Systems:** Linux (compiled my own kernel), systemd internals, QEMU/KVM, Unix tooling

**Secondary**
- Go, Python, Java, C# — enough to get things done
- Matplotlib (exploring), basic ML (regression models)

---

## Projects

### 🔧 [avr-rtos](https://github.com/JosepRDA/avrtos) *(in progress)*
A minimal preemptive RTOS for AVR 8-bit microcontrollers, written in C++ and AVR Assembly.  
Implements a cooperative + preemptive scheduler, context switching via timer interrupts, and a basic task API.  
**Stack:** C, AVR Assembly, avr-gcc, QEMU (simavr)

---

### 🌐 [chat-application](https://github.com/JosepRDA/chat-application)
Bidirectional TCP client/server over localhost — both sides read and write simultaneously using threads.  
**Stack:** C, POSIX sockets, threads, networking

---

## What I'm studying right now

- OS internals (scheduling, virtual memory, IPC) — building a RTOS is teaching me more than any textbook
- GPU pipeline architecture
- Physics simulation (long-term goal: write a physics engine in C++)

---

## Setup

- OS: Linux (CachyOS + Arch)
- Editor: (Neovim and VS Code)
- Hardware: (AVR mcus, Xtensa architecture, good knowledge of x86 intrinsics, currently looking up to learning CUDA)
