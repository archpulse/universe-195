# Appendix B. Universe 195 IT Glossary


Not every reader runs Arch Linux or compiles custom kernels on Friday nights! This guide explains all IT terms, commands, and tech concepts from the book and stories in plain, simple terms.

---

### 💻 1. Terminal & Operating Systems

* **Linux / Arch Linux**: An open-source operating system. Unlike Windows, Arch Linux requires users to assemble and configure everything manually from text configuration files. Considered the ultimate badge of tech geek pride.
* **Hyprland / dotfiles**: Hyprland is a modern tiling window manager for Linux that automatically arranges windows into a grid. `dotfiles` are text configuration files used to customize dot-prefixed settings for apps and desktops.
* **journalctl**: A Linux system utility used to inspect kernel and service log journals (`journalctl -k`). This is how Archpulse spotted Universe 195's kernel debug string.
* **sysctl**: A Linux command used to modify kernel parameters in runtime memory on the fly without needing a system reboot.

---

### ⚛️ 2. Physics & Quantum Computing

* **FPS (Frames Per Second)**: The frequency of consecutive images displayed per second. Higher FPS means smoother animation (60+ FPS is standard, 240+ FPS is competitive esports level).
* **Planck Time (\(5.39 \times 10^{-44}\) s)**: The smallest theoretical unit of time in physics. Interpreted in the book as reality's "fundamental frame rate" (\(\approx 1.85 \times 10^{43}\) FPS).
* **Quantum Computer (Qubit vs Bit)**: Classical CPUs operate on binary bits (`0` or `1`). Quantum computers use qubits (which can exist in superposition as both `0` and `1` simultaneously). A quantum PC cannot directly execute Java or Minecraft—it solves specialized mathematical matrices.

---

### 🐙 3. Software Development (Git & Stack Overflow)

* **Git / GitHub**: A version control system. It tracks code history, manages branches, and lets developers publish code globally.
* **Commit**: Saving a snapshot of code changes along with a descriptive message (e.g., `git commit -m "fix: not a bug"`).
* **Push / Pull**: `push` uploads local commits to a remote server; `pull` fetches the latest remote commits to your machine.
* **Fork**: Creating an independent copy/branch of someone else's repository (e.g., creating Universe 196 as a fork of 195).
* **Rollback**: Restoring a system to a previous known-good state following an incident or failure.
* **Stack Overflow**: The world's most famous Q&A platform for programmers. A **snippet** is a small block of copied code pasted without deep comprehension (Milo's favorite technique).

---

### 🚨 4. Errors & System Failures

* **NullPointerException (NPE)**: An error that occurs when a program tries to access an object that points to nothing/null in memory (in the book: accessing the void).
* **Out-of-Memory (OOM)**: A catastrophic condition where a system runs completely out of RAM, forcing the OS to terminate processes or crash the cluster.
* **Deadlock**: A situation where two threads are mutually waiting for each other to release a lock, freezing the system permanently.
* **Kernel Panic**: A fatal operating system kernel error where system execution halts completely, requiring an immediate reboot.

---

### 🌐 5. Networking, Web & Specs

* **HTTP Header**: Metadata transmitted between a web client and server (e.g., `HTTP/1.1 200 OK` indicates successful request processing).
* **Hypervisor**: Low-level software that runs and isolates multiple virtual machines (or Universes!) on a single physical server cluster.
* **LLM / ChatGPT / Context Window**: Large Language Model. The context window is the memory buffer determining how many preceding conversation tokens the model remembers.
* **RFC (Request for Comments)**: An official technical specification document defining Internet standards and protocols (e.g., *RFC-195-COFFEE: The Coffee Constant*).
* **Swagger / OpenAPI / JSON / YAML**: Strict specification and validation formats for web APIs. In Story 2, validating every electron against OpenAPI specs collapsed Universe 182 into a `.yaml` black hole.