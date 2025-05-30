# 🔄 4-bit Universal Shift Register (USR)

## 📌 Description

This project implements a 4-bit Universal Shift Register (USR) in Verilog using Intel Quartus Prime. The register supports four operations:

- **Hold** (No change)
- **Shift Right**
- **Shift Left**
- **Parallel Load**

## 🖼️ RTL Schematic


> ![RTL]([path/to/rtl_image.png](https://github.com/Nithyanand-b/4-Bit-Universal-Shift-Register/blob/main/Screenshot%202025-05-30%20212127.png))

---

## 🔧 Technologies Used

- Verilog HDL  
- Intel Quartus Prime Lite Edition

## 💡 Mode Control Table

| Mode | Operation     |
|------|---------------|
| 00   | Hold          |
| 01   | Shift Right   |
| 10   | Shift Left    |
| 11   | Parallel Load |

## 📂 Project Files

- `four_bit_USR.v` — Verilog source code  
- `four_bit_USR.qsf` / `four_bit_USR.qpf` — Quartus project and settings files  
- `output_files/*.sof` — FPGA programming file  
- `pin_assignments.txt` — Pin mappings (if using an FPGA board)

---

## 👨‍💻 Author

Designed by Nithyanand Boopathi
📅 Date: April 30 2025

