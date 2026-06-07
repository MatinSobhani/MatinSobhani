# Hi, I'm Matin 👋

I'm a Computer Engineering student at UC Santa Cruz focused on **digital hardware, FPGA design, RTL design, and verification**. I enjoy building hardware/software systems that connect low-level design with real world behavior, from FPGA image-processing pipelines to embedded sensing systems.

Currently, I'm especially interested in:

- FPGA and ASIC design
- RTL design with Verilog/SystemVerilog
- Design verification with cocotb and UVM
- Embedded systems and hardware/software integration
- Computer architecture and digital logic

## 🛠️ Technical Skills

**Hardware / Verification**  
Verilog, SystemVerilog, FPGA Design, RTL Design, cocotb, UVM, Vivado, Verilator, Icarus Verilog, Yosys

**Programming**  
C++, Python, RISC-V Assembly, JavaScript

**Tools**  
Git, Linux, VS Code, Jupyter Notebook, Oscilloscope, Ghidra, Burp Suite

## 🚀 Featured Projects

### FPGA Sobel Image Processing
A SystemVerilog FPGA image processing pipeline that performs Sobel edge detection on image data streamed over UART.

- Built a ready/valid streaming pipeline: RGB → grayscale → Sobel → magnitude
- Used synchronous on-chip RAM for the sliding 3x3 image window
- Verified modules with cocotb testbenches
- Demonstrated the full design on hardware and reconstructed processed frames in Python/Jupyter

[View Project](https://github.com/MatinSobhani/FPGA-Image-Processing)

### Wildfire Detection System
A senior design project built with a 7-person team to detect early wildfire presence using drone and ground-station hardware.

- Integrated ESP32-based hardware, camera input, GPS telemetry, and a live web map
- Used YOLOv8-based fire detection and cloud-based reporting
- Built an end-to-end geolocation pipeline to estimate and display fire locations

### Osmosis FPGA Game
An FPGA VGA game implemented using synchronous Verilog logic.

- Generated a 640x480 VGA display on a BASYS3 board
- Designed FSMs for motion, collision behavior, game flow, timing, and controls
- Verified Hsync/Vsync timing and active video behavior with a testbench

[View Project](https://github.com/MatinSobhani/FPGA-Osmosis-Game)

## 📚 Education

**University of California, Santa Cruz**  
B.S. Computer Engineering: Digital Hardware  
Minor in Computer Science  
Expected August 2026

**El Camino College**  
A.S. Mathematics, Honors  
A.S. Physics, Honors

## 👨‍🏫 Experience

I'm currently an Engineering Tutor for an upper-division digital logic course at UC Santa Cruz, where I help students with Boolean algebra, finite-state machines, timing analysis, and Verilog debugging.
