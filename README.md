# Container Papers

## Design on Secure Containers

1. Drawbridge-Rethinking the library OS from the top down

2. OSv-Optimizing the Operating System for Virtual Machines, which is a new OS designed to run single application

3. LightVM-My VM is Lighter (and Safer) than your Container

4. Graphene-SGX- A Practical Library OS for Unmodified Applications on SGX

5. Directvisor-Virtualization for Bare-metal Cloud

6. Firecracker- Lightweight Virtualization for Serverless Applications.pdf

7. X-Containers-Breaking Down Barriers to Improve Performance and Isolation of Cloud-Native Containers


## Books

1. Hardware and Software Support for Virtulization

## Blogs

2. VirtFS 虚拟化技术简介


## Compare Secure Containers

1. Blending Containers and Virtual Machines- A Study of Firecracker and gVisor


## Optimization: FS Sharing 

0. 9p filesystem protocol https://www.kernel.org/doc/html/latest/filesystems/9p.html https://github.com/torvalds/linux/tree/master/fs/9p https://github.com/torvalds/linux/tree/master/net/9p

1. XCPU & Clustering http://xcpu.org/papers/xcpu-talk.pdf

2. KVMFS: control file system for KVM http://xcpu.org/papers/kvmfs.pdf

3. CellFS: A New Programming Model for the Cell BE http://xcpu.org/papers/cellfs-talk.pdf

4. PROSE I/O: Using 9p to enable Application Partitions http://plan9.escet.urjc.es/iwp9/cready/PROSE_iwp9_2006.pdf

5. VirtFS: A Virtualization Aware File System pass-through http://goo.gl/3WPDg



## Related Open Source Projects

### Linux Binary Compatible
- [UML](http://user-mode-linux.sourceforge.net/) User-Mode Linux
- [OSv](http://osv.io) - Modular unikernel able to execute unmodified Linux binaries, developed in C++.
- [Nanos](https://github.com/nanovms/nanos) - Linux binary compatible unikernel focused on security.
- [HermiTux](https://github.com/ssrg-vt/hermitux) - Research project from Virginia Tech, demonstrating advanced optimizations.

### Language oriented
- [HaLVM](https://galois.com/project/halvm) - Port of Glasgow Haskell compiler producing Xen optimized unikernels.
- [LING](https://github.com/cloudozer/ling) - Erlang/Elixir unikernel development toolkit targeting Xen.
- [MirageOS](https://mirage.io) - OCaml unikernel development library using OCAML on XEN. 
- [runtime.js](http://runtimejs.org) - KVM oriented unikernel for running JavaScript applications via the V8 engine.
- [IncludeOS](https://github.com/includeos/IncludeOS) - Feature rich unikernel development library for C++.
- [Toro Kernel](https://torokernel.io) - Lazarus/FreePascal toolkit for unikernel development.
- [Ultibo Core](https://github.com/ultibohub/Core) - Lazarus/FreePascal unikernel targeting Raspberry Pi as the runtime environment.
- [rekernel](https://github.com/imbsky/rekernel) - Minimal setup for developing unikernels in ReasonML.
- [Union](https://github.com/pmuens/union) - POSIX compliant unikernel written in Rust.
- [binaryno](https://github.com/gmodena/binaryno) - Rust unikernel running on bare ARM CortexM hardware.

### Generic
- [ClickOS](http://cnp.neclab.eu/projects/clickos) - Efficient network function virtualization platform, optimized for Xen and developed by NEC, A high-performance, virtualized software middlebox platform (e.g., for NFV).
- [Clive](http://lsub.org/ls/clive.html) - Research project from Rey Juan Carlos University (Madrid), developed in Go, an OS designed to work in distributed and cloud environments.
- [Mini-OS](https://wiki.xen.org/wiki/Mini-OS) - Reference kernel distributed with Xen.
- [Rump Kernels](http://rumpkernel.org) - Development platform reusing NetBSD components for producing efficient unikernels, running unmodified POSIX software as a unikernel
- [Firecracker](https://firecracker-microvm.github.io) - AWS's VM isolation engine, using in products such as Lambda and Fargate.
- [Unikraft](https://xenproject.org/developers/teams/unikraft) - Collection of building blocks for unikernel development.
- [BareMetal](https://github.com/ReturnInfinity/BareMetal) - Self described as an exokernel, it can be used as the starting point for unikernel development.
- [HermitCore](https://github.com/hermitcore/libhermit) - A C-based, lightweight unikernel project from Aachen University.
- [unicycle](https://github.com/libunicycle/unicycle) - Unikernel application framework developed in C.
- [EbbRT](https://github.com/SESA/EbbRT) - Boston University unikernel research project.
- [Nautilus](https://github.com/HExSA-Lab/nautilus) - Aerokernel from Sandia National Laboratories, supporting bare metal x86_64 and Xeon Phi.
- [JML](https://github.com/yesco/jml) - Proof of concept for a minimal web server unikernel implementing its own language.
- [UNICORE](http://unicore-project.eu) - Common code base and toolkit for deployment of applications to secure and reliable execution environments.

### Unikernel-like
- [Drawbridge](https://www.microsoft.com/en-us/research/project/drawbridge) - Research prototype platform from Microsoft.
- [Graphene](https://github.com/oscarlab/graphene) - Library OS optimized for Intel SGX.


## Tools

- [OPS](https://ops.city) - Orchestration tool for building and deploying Nanos based images.
- [Capstan](http://osv.io/capstan) - Orchestration tool for packaging and running OSv based images.
- [UniK](https://github.com/solo-io/unik) - Unikernel compiler supporting a Firecracker, rump kernels, OSv, IncludeOS and MirageOS.
- [Solo5](https://github.com/Solo5/solo5) - Middle-ware interfacing unikernels with the host systems.
- [Albatross](https://github.com/hannesm/albatross) - MigrageOS unikernel orchestration, via Solo5.
