# 4-bit CPU (Logisim)

A custom-built 4-bit CPU designed using Logisim to simulate a simple processor architecture.  
This project explores digital logic design, instruction control flow, and jump-based execution using ROM.

I'm actively developing and planning to extend it with Verilog-based HDL implementation.

---

## 🚀 Features

- **4-bit Register A and B**
- **ALU** with Add/Subtract operation (controlled via MUX)
- **Flags**: Zero, Carry, Negative (for conditional jumps)
- **Output Register** with 7-segment HEX display
- **ROM** with 16 custom instructions (HEX-programmed)
- **Jump Control Unit** using flags and multiplexer logic
- **Program Counter** and ROM address control via flags (zero/carry/negative)

---

## 🧠 Learning Highlights

- Implemented instruction execution using ROM and control logic
- Designed arithmetic operations without pre-built components
- Integrated MUX/DEMUX logic to simulate control paths
- Explored basic instruction decoding and condition-based branching
- Gained deep understanding of CPU flags, timing, and ROM logic

---

## 🖥️ How to Use

1. Open the project in **Logisim**
2. Press the **clock button** to step through instructions
3. Monitor the **HEX display** and flag LEDs for output/state
4. Update **ROM contents** using your own HEX-coded instructions

---

## 📸 Screenshot  
![![{4-bit CPU screenshot}](https://github.com/yourusername/your-repo-name/blob/main/screenshot.png)

---

## 📄 Instruction Set Example (ROM)

| Address | HEX Code | Description         |
|---------|----------|---------------------|
| `0x0`   | `1F`     | Load 1 to Reg A     |
| `0x1`   | `4F`     | Load F to Reg B     |
| `0x2`   | `20`     | Add A + B           |
| `0x3`   | `C6`     | If Carry, jump to 6 |
| `0x4`   | `00`     | No operation        |

---

## 🔧 Next Goals

- Add instruction decoder block  
- Extend to 8-bit version  
- Rebuild in Verilog for HDL simulation  
- Add RAM for data operations

---

## 🧑‍💻 Author

Made with curiosity by a second-year **Electrical Engineering** student passionate about CPU architecture and embedded systems.

