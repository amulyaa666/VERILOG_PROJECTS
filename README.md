# 🔢 4-Bit Adder in Verilog (Vivado)

## 📌 Project Overview
This project implements a **4-bit binary adder** using **Verilog HDL**.  
It is designed, simulated, and tested in **Xilinx Vivado**.

The adder takes:
- Two 4-bit inputs (`A` and `B`)
- One carry input (`Cin`)

It produces:
- A 4-bit sum (`Sum`)
- One carry output (`Cout`)

---

## 🛠 Tools & Technologies
- **Xilinx Vivado Design Suite**
- **Verilog HDL**

---

## 📂 Files in This Repository
| File Name           | Description |
|---------------------|-------------|
| `adder_4bit.v`      | Verilog source code for the 4-bit adder |
| `tb_adder_4bit.v`   | Testbench file for simulation |
| `README.md`         | Project documentation |

---

## ⚙ How It Works
1. Each bit is added using a **Full Adder**.
2. The carry from each bit is propagated to the next.
3. The final carry is given as `Cout`.

**Full Adder Logic:**
