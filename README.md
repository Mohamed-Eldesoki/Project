# Mano Basic Computer - Verilog Simulation Project

## 🎬 Project Demo

📽️ **Watch the Simulation in Action**  
Check out our full video demonstration of the Mano Basic Computer simulation here:  
👉 [Project Video Demo](https://drive.google.com/drive/folders/1sENxmsi0irYrGAmYCvUyOXRNzETVGUr_?usp=sharing)

---

## 🖥️ Overview

The **Mano Basic Computer** is a simplified processor architecture introduced by **Morris Mano**. It is widely used in educational settings to demonstrate how a CPU **fetches, decodes, and executes** instructions step by step.

This project simulates the **Mano Basic Computer architecture** using **behavioral Verilog modules**, offering a complete overview of how such a basic system operates.

---

## ⚙️ Architecture Components

- **Internal Registers**:  
  - `PC`, `AC`, `AR`, `DR`, `IR`, `TR`, `INPR`, `OUTR`
- **Memory Module**:  
  - 4096 × 16 bits
- **ALU** and `E` flip-flop
- **Control Logic** and **Sequence Counter (SC)**
- **Common Data Bus**: 16-bit
- **Instruction Decoder**

---

## 🛠️ Project Files

| File Name            | Description                                         |
|---------------------|-----------------------------------------------------|
| `BasicComputer.v`    | Top module of the Basic Computer                   |
| `BasicComputer_tb.v` | Testbench to activate `BasicComputer` DUT          |
| `Memory_Data.txt`    | Contains the instructions to be loaded in memory   |

### ✅ Supported Instructions

Includes both **memory-reference** and **register-reference** instructions such as:

- `LDA`, `ADD`, `STA`, `ISZ`, `INC`
- `CLE`, `CIR`, `CME`, `CIL`, `AND`

More details can be found in the `Memory_Data.txt` file.

---

## 👥 Team (Team ID: 8208)

1. Mohamed Adel Elsayed Eldesoky  
2. Ahmed Mohamed Farag Metwally  
3. Mohamed Ali Elsayed Elashry  
4. Khaled Yasser Elsayed Khedr  
5. Alaa Ashraf Elsayed Metwally  
6. Haneen Emad Elsayed Badawy

---

## 📌 Note

This project is purely educational and designed to help students understand how CPU components and instruction cycles function at the architecture level.
