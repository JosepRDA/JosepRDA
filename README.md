# José Paulo Araújo

> Embedded systems developer, systems programmer, and CS student.  
> Currently building a bare-metal RTOS for AVR 8-bit from scratch.

---

## What I work with

**Core stack**
- **Languages:** C, C++, Rust, Assembly (AVR, x86)
- **Domains:** Embedded systems, RTOS, OS internals, computer architecture, electronics
- **Graphics:** OpenGL, WebGPU (learning Vulkan next)
- **Systems:** Linux (compiled my own kernel), systemd internals, QEMU/KVM, Unix tooling (specially GNU binutils)

**Secondary**
- Go, Python, Java, C# — enough to get things done
- OpenCV (exploring), basic ML (regression models)

---

## Projects

### 🔧 [avr-rtos](https://github.com/JosepRDA) *(in progress)*
A minimal preemptive RTOS for AVR 8-bit microcontrollers, written in C++ and AVR Assembly.  
Implements a cooperative + preemptive scheduler, context switching via timer interrupts, and a basic task API.  
**Stack:** C, AVR Assembly, avr-gcc, QEMU (simavr)

---

### 🎮 rust-tracer *(Rust)*
A basic raytracer built from scratch — no external rendering libraries.
**Stack:** Rust, linear algebra from scratch


---

### 🌐 [Simple-Network](https://github.com/JosepRDA/Simple-Network)
Bidirectional TCP client/server over localhost — both sides read and write simultaneously using threads.  
**Stack:** C, POSIX sockets, pthreads

---

### 🦀 ESP-IDF Template Fork
Frozen snapshot of the esp-idf Rust template at a stable stage for personal embedded Rust experiments.  
**Stack:** Rust, CMake, ESP-IDF

---

## What I'm studying right now

- OS internals (scheduling, virtual memory, IPC) — building a RTOS is teaching me more than any textbook
- GPU pipeline architecture
- Physics simulation (long-term goal: write a physics engine in C++)

---

## Setup

- OS: Linux (CachyOS + Arch)
- Editor: (Neovim and VS Code)
- Hardware: (AVR mcus, Xtensa esp32 architecture)
