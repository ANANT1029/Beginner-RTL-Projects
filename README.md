# 2:1 Multiplexer – Verilog

## 🧠 Objective
Design and simulate a 2:1 MUX using behavioral Verilog.

## 🔧 Tools
- Icarus Verilog
- GTKWave

## 📁 Files
- `mux2_1.v` – Verilog code
- `tb_mux2_1.v` – Testbench

## ▶️ How to Run
```bash
iverilog tb_mux2_1.v mux2_1.v -o mux
./mux
gtkwave dump.vcd
