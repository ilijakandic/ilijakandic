## Ilija Kandić

Final-year software engineering student at the School of Electrical Engineering,
University of Belgrade.

The repositories below are my coursework, cleaned up and documented. Most of it
sits close to the machine: an assembler and linker, a preemptive kernel, a
hypervisor driving KVM through raw ioctls.

### Systems

| | |
|---|---|
| [asm-linker-emulator](https://github.com/ilijakandic/asm-linker-emulator) | Assembler, linker and emulator for a 32-bit instruction set, written from scratch in C++17 |
| [kvm-hypervisor](https://github.com/ilijakandic/kvm-hypervisor) | Type-2 hypervisor on the Linux KVM ioctl API, with bare-metal x86-64 guests and copy-on-write shared files |
| [riscv-kernel](https://github.com/ilijakandic/riscv-kernel) | Preemptive multithreaded RISC-V kernel — threads, scheduler, semaphores, allocator, syscalls |
| [xv6-slab-allocator](https://github.com/ilijakandic/xv6-slab-allocator) | Linux-style SLAB allocator over a buddy allocator, added to MIT's xv6-riscv |

### Backend and web

| | |
|---|---|
| [jms-ecommerce](https://github.com/ilijakandic/jms-ecommerce) | Distributed backend: three subsystems with separate databases, integrated only over JMS queues behind a JAX-RS gateway |
| [cagemax](https://github.com/ilijakandic/cagemax) | Django app for running an MMA club — training logs, weight-cut tracking, events and fight records |

