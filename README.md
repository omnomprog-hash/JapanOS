# 🇯🇵 JapanOS

**JapanOS** is an experimental open-source operating system built from scratch.

The project focuses on creating a complete operating system ecosystem with its own kernel, driver system, executable formats, development tools, graphics stack, and user-space environment.

> ⚠️ JapanOS is currently under active development. APIs, file formats, and system components may change.

## ✨ Features

* 🖥️ Custom operating system kernel
* 🥾 Limine bootloader
* 💾 FAT32 filesystem support
* ⌨️ Keyboard support
* 🐚 Custom shell
* 🔌 Custom `.drv` driver format
* 📦 `.japp` application format
* 🎨 JapanGUI graphical interface
* 🎮 JapanGL graphics library
* 🧠 JCC compiler
* ⚙️ JASM assembler
* 🔗 JLD linker
* 🧩 JML mod loader
* 🛠️ JIDE development environment

## 🏗️ Architecture

JapanOS is primarily designed for **x86-64** systems.

The planned software structure is:

```text
JapanOS
├── Kernel
├── Drivers
│   └── *.drv
├── System
│   └── *.sys
├── Applications
│   └── *.japp
├── JapanGUI
├── JapanGL
├── JCC
├── JASM
├── JLD
└── JML
```

## 📦 File Formats

### `.drv`

The native JapanOS driver format.

Drivers are designed to provide hardware and system functionality while communicating with the operating system through the JapanOS driver API.

### `.japp`

The native JapanOS application format.

It is designed for executable user-space applications.

### `.sys`

System modules used by JapanOS.

System modules can communicate with the kernel and load required drivers through the system API.

## 🛣️ Roadmap

### JapanOS 0.x

* [x] Kernel boot
* [x] Basic filesystem
* [x] FAT32 support
* [x] Basic shell
* [x] Initial keyboard support
* [ ] User Space
* [ ] System calls
* [ ] Virtual File System
* [ ] Advanced driver system
* [ ] Process management
* [ ] Memory management improvements

### JapanOS 1.0

* [ ] JapanGUI
* [ ] USB keyboard
* [ ] USB mouse
* [ ] SATA SSD support
* [ ] Wi-Fi support
* [ ] Internet networking
* [ ] HTML/CSS/DOM environment

### JapanOS 2.0+

* [ ] JCC
* [ ] JASM
* [ ] JLD
* [ ] `.japp`
* [ ] JapanGL
* [ ] JIDE
* [ ] JML
* [ ] Advanced graphics subsystem
* [ ] Additional hardware drivers

### JapanOS 3.0

* [ ] NVMe support
* [ ] Advanced device management
* [ ] Improved multitasking
* [ ] SMP support
* [ ] Advanced security features

## 🔧 Building

JapanOS development uses tools such as:

* GCC / Cross-GCC
* NASM
* Limine
* QEMU
* GNU Make
* GNU Binutils

Example QEMU command:

```bash
qemu-system-x86_64 -drive format=raw,file=build/JapanOS.img -m 512M
```

## 🧪 Project Status

JapanOS is an **experimental open-source operating system**.

The project is not intended to be a production-ready operating system yet.

Kernel APIs, application formats, driver interfaces, directory structures, and other components may change during development.

## 🤝 Contributing

Contributions, bug reports, ideas, documentation, and code improvements are welcome.

To contribute:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Test your changes.
5. Open a Pull Request.

## 💰 Supporting JapanOS

Developing an operating system requires time, hardware, testing infrastructure, and development resources.

Financial support can help the project with:

* 🖥️ Hardware for driver testing
* 🌐 Servers and infrastructure
* ⚙️ CI/CD infrastructure
* 📦 Hosting and distribution
* 🧪 Hardware compatibility testing
* 🔧 Development tools
* 📚 Documentation

All project funding should be used to support the development and infrastructure of JapanOS.

## 📜 License

The project license is provided in [`LICENSE`](LICENSE).

## 🌸 Vision

JapanOS aims to become more than just a kernel.

The long-term goal is to create an independent operating system ecosystem with:

**Kernel → Drivers → User Space → GUI → Applications → Development Tools**

## 🚀 JapanOS

> **Build it. Understand it. Make it yours.**

**JapanOS Team**