# 4-bit Universal Shift Register (USR)

## 📌 Description
This project implements a 4-bit Universal Shift Register in Verilog using Intel Quartus Prime. The register supports:
- Hold
- Shift Right
- Shift Left
- Parallel Load

## 🔧 Technologies Used
- Verilog HDL
- Intel Quartus Prime Lite Edition
- FPGA (Cyclone IV, EP4CE10F17C8 used for testing)

## 💡 Mode Table

| Mode | Function      |
|------|---------------|
| 00   | Hold          |
| 01   | Shift Right   |
| 10   | Shift Left    |
| 11   | Parallel Load |

## 📂 Files
- `four_bit_USR.v` — Verilog source
- `four_bit_USR.qsf/qpf` — Quartus project and settings
- `output_files/*.sof` — Programming file for FPGA
- `pin_assignments.txt` — Board-specific pin mapping (optional)

## 🚀 How to Run
1. Open `four_bit_USR.qpf` in Quartus Prime
2. Compile the project
3. Assign FPGA pins in Pin Planner
4. Program the board using USB-Blaster

## 🖥️ Simulation (Optional)
Simulate using University Waveform Editor (`.vwf`) in Quartus.

