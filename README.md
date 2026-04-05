<div align="center">

# 🚀 BHANU PRAKASH

### ⚡ Transforming Complex RTL into Silicon-Proven Reality

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,70:003366,100:00ccff&height=250&section=header&text=BHANU%20PRAKASH&fontSize=70&animation=fadeIn&fontAlignY=35&v=1" width="100%" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ch-bhanu-prakash-61b156318)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bhanuprakash1420@gmail.com)
[![Location](https://img.shields.io/badge/Location-Bengaluru%2C%20India-orange?style=for-the-badge)](#)
[![Company](https://img.shields.io/badge/Working%20At-SION%20Semiconductors-blue?style=for-the-badge)](#)

*“Hardware is easy to design, but verification is where the real battle is won. I specialize in finding the bugs before the fab does.”*

</div>

<br>

---

## 👨‍💻 About Me

Welcome to my GitHub! I am a dedicated **SoC Verification Engineer** currently contributing my expertise at **SION Semiconductors** in Bengaluru. My daily engineering life revolves around the fascinating intersection of hardware design and software engineering—specifically, using advanced Object-Oriented Programming (OOP) concepts to verify complex digital hardware.

- 🔭 **Currently Working On:** Developing comprehensive UVM (Universal Verification Methodology) environments for complex AMBA-based IPs.
- 🌱 **Currently Learning:** Advanced PCIe protocol intricacies and AI-driven hardware verification techniques.
- 👯 **Looking to Collaborate On:** Open-source VIP (Verification IP) development, RISC-V verification, and FPGA acceleration projects.
- 🤔 **Looking for Help With:** Integrating Python-based machine learning models into traditional SystemVerilog verification flows.
- 💬 **Ask Me About:** SystemVerilog Assertions (SVA), UVM Phasing, Coverage Closure strategies, and AXI4 transactions.
- 📫 **How to reach me:** Drop me a message on [LinkedIn](https://www.linkedin.com/in/ch-bhanu-prakash-61b156318).

<br>

---

## 📊 GitHub Analytics & Code Science

*Quantifying my engineering journey through real-time metrics.*

<div align="center">

### 📈 Weekly Contribution Patterns
<img src="https://github-readme-activity-graph.vercel.app/graph?username=Bhanu-Prakash-CH1221&theme=tokyonight&area=true&hide_border=true&v=1" width="100%" />

### 🏆 Profile Summary Statistics
<img width="48%" src="https://github-readme-stats.vercel.app/api?username=Bhanu-Prakash-CH1221&show_icons=true&theme=tokyonight&count_private=true&include_all_commits=true&v=1" />
<img width="48%" src="https://streak-stats.demolab.com/?user=Bhanu-Prakash-CH1221&theme=tokyonight&hide_border=true&v=1" />

### 💻 Technology Distribution
<img width="80%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Bhanu-Prakash-CH1221&layout=compact&theme=tokyonight&langs_count=10&v=1" />

</div>

<br>

---

## 🛠️ Comprehensive Technical Stack

### 🧠 1. Core Languages & Methodologies
| Technology | Proficiency & Application |
| :--- | :--- |
| **SystemVerilog (SV)** | Extensive use of OOP, Randomization, Mailboxes, Semaphores, and IPC for testbench creation. |
| **UVM 1.2** | Mastery of Factory Overrides, Phases, Config DB, Sequences, and virtual interfaces. |
| **Verilog HDL** | Writing RTL code for synthesis, structural, dataflow, and behavioral modeling. |
| **C / C++** | Used for DPI-C (Direct Programming Interface) to interface hardware models with C code. |
| **Python** | Scripting for automated log parsing, regression launching, and bit-stream manipulation. |
| **Bash / Shell** | Makefile creation and environment setup in Linux/Unix operating systems. |

### 🔌 2. Bus Protocols & Interfaces
| Protocol | Expertise Level & Details |
| :--- | :--- |
| **AMBA AXI4 / AXI-Lite** | Burst transfers, Out-of-order execution, Interleaving, Master/Slave interconnects. |
| **AMBA AHB / APB** | Pipelined transfers, split transactions, low-power peripheral interfacing. |
| **I2C / SPI / UART** | Serial communication protocols, verified using custom-built SV/UVM monitors and drivers. |
| **PCIe (Learning)** | Exploring Transaction Layer Packets (TLPs) and Data Link Layer mechanics. |

### 🧪 3. EDA Tools & FPGA Platforms
| Category | Tools |
| :--- | :--- |
| **Simulation / Verification** | Siemens QuestaSim, Mentor Graphics ModelSim, Synopsys VCS, Cadence Xcelium. |
| **Synthesis & FPGA** | Xilinx Vivado, Intel Quartus Prime, Xilinx ISE. |
| **Waveform Debugging** | GTKWave, Synopsys Verdi, ModelSim Wave window. |
| **Target Hardware** | Xilinx Zynq-7000 SoC, Artix-7, Basys 3 boards. |
| **Version Control** | Git, GitHub, Bitbucket. |

<br>

---

## ⚙️ My Verification Philosophy & Workflow

A successful verification cycle isn't just about writing tests; it's about systematically eliminating the possibility of failure. Here is my standard workflow for IP/SoC Verification:

1. **Specification Analysis:**
   - Deep dive into the architectural spec.
   - Extracting features and writing a comprehensive Verification Plan (vPlan).
2. **Environment Architecture:**
   - Deciding on the UVM topology (Active/Passive agents).
   - Defining transaction items (`uvm_sequence_item`) to capture protocol specifics.
3. **Component Development:**
   - Building constraint-driven random stimulus generators (Sequences).
   - Developing cycle-accurate Drivers and passive Monitors.
   - Creating reference Golden Models (Predictors) within the Scoreboard.
4. **Coverage Implementation:**
   - Writing SystemVerilog Assertions (SVA) for protocol checking.
   - Defining Covergroups and Coverpoints for Functional Coverage closure.
5. **Regression & Debug:**
   - Running massive randomized regressions with different seed values.
   - Using Verdi/Questa to trace signals back to RTL logic flaws.

<br>

---

## 📂 Featured Project Deep-Dives

### 🛡️ [Advanced Peripheral Bus (APB) Verification IP (UVM)](https://github.com/Bhanu-Prakash-CH1221/apb_vip-master)

**Objective:** Design a fully reusable, modular Verification IP for the AMBA APB protocol using the Universal Verification Methodology (UVM).

**Architectural Highlights:**
- **UVM Sequences:** Implemented constrained random sequences for READ, WRITE, and back-to-back peripheral transfers. Includes error injection sequences to test `PSLVERR` assertion.
- **UVM Agent:** Highly configurable agent that can be switched between `UVM_ACTIVE` (driving the bus) and `UVM_PASSIVE` (monitoring only).
- **UVM Scoreboard:** Utilized a layered approach. The predictor receives stimulus from the monitor, computes expected data, and sends it to a UVM comparator to match against actual RTL output.
- **Coverage Driven:** Designed cross-coverage bins to ensure all address ranges and data permutations were hit during simulation. Achieved 100% functional and code coverage.

<details>
<summary><b>💻 Click to view a sample UVM Sequence Item structure</b></summary>

```systemverilog
// Sample snippet representing the thought process behind APB Sequence Items
class apb_seq_item extends uvm_sequence_item;
  
  // Randomize variables for constraints
  rand bit [31:0] paddr;
  rand bit [31:0] pwdata;
  rand bit        pwrite;
  rand bit        penable;
  
  // Non-randomized response variables
  bit [31:0]      prdata;
  bit             pslverr;

  // Constraints for standard 32-bit aligned transfers
  constraint addr_align_c { paddr % 4 == 0; }
  constraint addr_range_c { paddr inside {[32'h0000_0000 : 32'h0000_FFFF]}; }

  `uvm_object_utils_begin(apb_seq_item)
    `uvm_field_int(paddr,   UVM_ALL_ON)
    `uvm_field_int(pwdata,  UVM_ALL_ON)
    `uvm_field_int(pwrite,  UVM_ALL_ON)
    `uvm_field_int(prdata,  UVM_ALL_ON)
    `uvm_field_int(pslverr, UVM_ALL_ON)
  `uvm_object_utils_end

  function new(string name = "apb_seq_item");
    super.new(name);
  endfunction
endclass
