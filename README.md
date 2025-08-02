## Hi there 👋

<p align="center">
<a href="https://github.com/your-username">
<img src="https://avatars.githubusercontent.com/u/your-user-id?v=4" width="150" height="150" style="border-radius: 50%;">
</a>
</p>

<h1 align="center">
Hi there , I'm [Manal Ahmed]
</h1>

<p align="center">
A passionate and driven Electronics and Communication Engineering student with a deep interest in low-level systems, hardware design, and embedded systems. I thrive on building innovative solutions from the ground up, whether it's designing a single-cycle/Pipelined RISC-V processor or developing smart IoT systems.
</p>

<p align="center">
<a href="[https://www.linkedin.com/in/your-linkedin-profile](https://linkedin.com/in/manal-ahmed-8084b128a)" target="_blank">
<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
</a>
<a href="mailto:manalahmedmatheen@gmail.com">
<img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
</a>

</p>

⚡ Core Projects
🚀 RISC-V Pipelined Processor
Pipelined a single-cycle RISC-V processor into a 5-stage pipeline: Fetch, Decode, Execute, Memory, and Writeback.

Implemented an RV32I ISA in Verilog with arithmetic, logic, control, and memory operations.

Utilized ImmGen, ALU, and advanced forwarding and bypassing techniques to resolve data hazards; validated using waveform analysis.

🔢 FPGA-based Approximate Multiplier
Developed an 8-bit Verilog multiplier with LSB truncation to optimize power and logic complexity.

Compared exact vs. approximate outputs, calculated percent error, and flagged deviations.

Verified with testbench; displayed output on a 7-segment display using Vivado on Nexys 4 (Artix-7).

Simulated functionality and synthesized design in Vivado, confirming reduced hardware utilization.

🤖 Bare-metal UART & Virtual Memory OS
Developed a bare-metal UART driver for a Raspberry Pi 2 in ARMv7-A AArch32 using assembly/C.

Designed a 2-level page table (4KB) for virtual memory using ARM MMU, isolating kernel (0x8000+) and user (0x100000+) spaces.

Restricted MMIO access (UART0 at 0x3F201000) to the kernel-only via MMU protection.

Implemented a syscall interface using SVC for EL0-to-EL1 UART output via printf().

Supported user program loading at 0x100000 with MMU-based access control and debug trapping.

🚗 IoT Smart Parking System
Built a real-time sensor-based slot detection system using Ultrasonic sensors, Arduino, and Raspberry Pi.

Coded in Python to process data and push updates to a live dashboard.

Supported modular multi-lot design for scalable smart city integration.

🛠️ Technical Skills
HDLs: Verilog, SystemVerilog

Programming: C, Python, Assembly (Cortex M-3)

Tools: Vivado, Nexys 4, GTKWave, QEMU, Keil, WSL

Technical Interests: ARMv7-A(AArch32), Bare-metal, Digital Hardware, RISC-V, AXI, Cortex M3, O.S.

Certifications: Advanced ML, Supervised ML, Unsupervised ML, Google DSC Intro to LLMs


