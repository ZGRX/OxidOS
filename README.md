# OxidOS

[English](#english-version) | [中文版](#中文版)

---

<a name="english-version"></a>
## English Version
**OxidOS** is a 64-bit operating system kernel written from scratch in **Rust**. 

Inspired by the [blog_os](https://github.com/phil-opp/blog_os) project, this is a journey into the deepest levels of software, exploring bare-metal programming, memory management, and hardware-software interaction without the safety net of an existing OS.

---

## 🎯 Goals
- **Zero Dependencies**: Building everything without the Rust standard library (`no_std`).
- **Memory Safety**: Bringing Rust's safety guarantees to the kernel level.
- **Learning by Doing**: Implementing CPU exception handling, paging, and multitasking from the ground up.

---

<a name="中文版"></a>
## 中文版
**OxidOS** 是一个受 [blog_os](https://github.com/phil-opp/blog_os) 启发，尝试使用 **Rust** 语言从零开始编写的 64 位操作系统内核。

这是一个纯粹的教育性质项目，旨在深入理解计算机底层架构、内存管理以及 Rust 在裸机环境下的表现。

---

## 🚀 项目愿景
- **从零开始**：不依赖于操作系统提供的标准库（`no_std`）。
- **内存安全**：利用 Rust 的所有权模型在内核级别避免常见的内存错误。
- **硬核实践**：手动处理 CPU 中断、分页、多任务处理等核心功能。
