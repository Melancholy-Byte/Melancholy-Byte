<div align="center">
  
# 👋 Hey, I'm Saurav Kumar (aka Melancholy-Byte)

`Building systems where algorithms meet silicon`

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=2000&color=37B3FF&center=true&vCenter=true&width=600&lines=Digital+Design+%7C+FPGA+%7C+Hardware+Accelerators;IIT+Engineer+crafting+high-speed+compute;Open-source+advocate+%26+collaboration+nerd)](https://git.io/typing-svg)

<p>
  <a href="mailto:saurav@example.com"><img alt="Email" src="https://img.shields.io/badge/Email-saurav%40example.com-red?style=flat-square"></a>
  <a href="https://www.linkedin.com/in/saurav-kumar"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat-square"></a>
  <a href="https://melancholy-byte.github.io"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-Live-181717?style=flat-square"></a>
</p>

<p>
  <img src="https://komarev.com/ghpvc/?username=Melancholy-Byte&style=flat-square&color=brightgreen" alt="Profile views" />
</p>

</div>

---

## 🧑‍🚀 About Me

- 🎓 IIT-trained hardware engineer focused on FPGA-accelerated math cores and embedded systems.
- ⚙️ Blend of algorithm design, hardware description, verification, and robotics.
- 🛰️ Passionate about reproducible research, open-source silicon, and collaborative engineering.
- 🧪 Currently exploring hybrid recursive multipliers, DSP datapaths, and autonomous systems.
- ✍️ Love documenting experiments so others can reproduce results fast.
- 🤝 Active collaborator on robotics, signal processing, and defense technology projects.

---

## 📌 Spotlight

| Area | Snapshot |
| --- | --- |
| 🔬 Current Focus | Hybrid Recursive Karatsuba Multiplications (HRKM) for latency/area wins on mid-range FPGAs. |
| 🧱 Stack | SystemVerilog · Verilog · VHDL · Verilator · Icarus · Vivado · Python · C++ · PlatformIO |
| 🏆 Highlights | IEEE ESL paper (Aug 2025) · Multi-width verification harness · FPGA implementations · Defense tech collaborations |
| 🤝 Open To | Collaborations on FPGA arithmetic, verification automation, robotics, DSP systems, and embedded applications. |

---

## 🧰 Tech Toolbox

| RTL & HDLs | Verification | Software | Embedded & Tools |
| --- | --- | --- | --- |
| SystemVerilog · Verilog · VHDL | Verilator · Icarus · cocotb · Pytest | Python · C++ · Bash · MATLAB | PlatformIO · Vivado · Git · GitHub Actions · Make |

---

## 🚀 Featured Projects

### 🔬 Research & Core Work

| Project | What It Does | Tech |
| --- | --- | --- |
| [**HRKM-FPGA**](https://github.com/Melancholy-Byte/HRKM-FPGA) | Hybrid Recursive Karatsuba Multiplier with FPGA implementations. Includes base, pipelined, adaptive, and compressed variants for area-time optimization. | Verilog, Vivado, FPGA Synthesis |
| [`HRKM`](#-hrkm-reference) | Hybrid recursive Karatsuba multiplier with OSBM cutoff for predictable FPGA timing. | SystemVerilog, Verilator, Icarus |

### 🤝 Collaborative Projects

| Project | Description | Tech & Focus |
| --- | --- | --- |
| [**AutonomousEV**](https://github.com/Melancholy-Byte/AutonomousEV) | Autonomous Electric Vehicle project - Lane detection, steering angle control, and ultrasonic sensing for autonomous navigation. | PlatformIO, Embedded C++, Python, Jupyter |
| [**DSP**](https://github.com/Melancholy-Byte/DSP) | Digital Signal Processing algorithms and implementations for real-time signal analysis and filtering. | Signal Processing, MATLAB, Python |
| [**Robotics-and-Autonomous-Systems**](https://github.com/Melancholy-Byte/Robotics-and-Autonomous-Systems) | Control systems and algorithms for autonomous robotic platforms with navigation and decision-making capabilities. | Embedded Systems, Control Theory, Sensors |
| [**LWS**](https://github.com/Melancholy-Byte/LWS) | Laser Warning System - Defense application for threat detection and alert systems. | Hardware Design, Embedded Systems, Defense Tech |
| [**Mini-project-24**](https://github.com/Melancholy-Byte/Mini-project-24) | Compact project demonstrating core hardware and software integration principles. | Mixed Hardware/Software |

### 🔧 Verilog Modules & Protocols

| Module | Description | Application |
| --- | --- | --- |
| [**Verilog**](https://github.com/Melancholy-Byte/Verilog) | Collection of Verilog modules including FIFO, FPGA implementations, and communication protocols (SPI, I2C, UART). | Data Pipeline, Memory Management, System Integration |

---

## 📈 GitHub Analytics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Melancholy-Byte&show_icons=true&theme=radical" alt="GitHub stats" />
  <img src="https://streak-stats.demolab.com?user=Melancholy-Byte&theme=radical" alt="GitHub streak" />
</div>

---

## 🤝 Let's Connect

- 💼 LinkedIn: `linkedin.com/in/saurav-kumar`
- 🌐 Portfolio: `melancholy-byte.github.io`
- ✉️ Email: `saurav@example.com`
- 🐦 Twitter: `@MelancholyByte`

Always happy to chat about FPGA design, verification tricks, or collaboration ideas.

---

## 📚 HRKM Reference

This section describes the Hybrid Recursive Karatsuba Multiplier (HRKM) work described in the paper "Hybrid Recursive Karatsuba Multiplications on FPGAs" (IEEE Embedded Systems Letters, Aug 2025).

### Implementations

- **[HRKM-FPGA](https://github.com/Melancholy-Byte/HRKM-FPGA)**: Complete FPGA implementation with base, pipelined, adaptive, and compressed variants. Ready for Vivado synthesis with comprehensive testbenches.

### Reference Implementation

The reference HDL implementation (if available) includes:
- `rtl/`: SystemVerilog RTL for OSBM (schoolbook), Karatsuba-2, and HRKM (recursive with hybrid cutoff)
- `tb/`: SystemVerilog testbench comparing HRKM vs built-in `*`
- `python/`: Pure-Python reference model for HRKM and vector generator

### HRKM-FPGA Quick Start

For the FPGA implementation, see the [HRKM-FPGA repository](https://github.com/Melancholy-Byte/HRKM-FPGA):

1. **Add to Vivado Project**: Import all RTL files from `rtl/` and `rtl/improvements/`
2. **Run Simulation**: Use testbenches in `tb/` folder (hrkm_tb_32, hrkm_tb_improved, etc.)
3. **Synthesize**: Set each variant as top module and run synthesis for area-time comparison

**Variants Available:**
- Base 32-bit/64-bit implementations
- Pipelined version (2× clock speed)
- Adaptive version (configurable leaf size)
- Compressed OSBM (optimized for area)

### Key Features

- **Hybrid Approach**: Recurses using Karatsuba until cutoff, then uses OSBM at leaves
- **Multiple Implementations**: Base, pipelined, adaptive, and compressed variants
- **FPGA Optimized**: Ready for Vivado synthesis with comprehensive testbenches
- **Parameterized**: Supports 32-bit and 64-bit operand widths

### License
This code is provided for academic/research use. Verify and adapt for your device/tool versions before deployment.
