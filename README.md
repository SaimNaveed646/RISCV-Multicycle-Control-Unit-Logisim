
# RISC-V Multicycle Control Unit | Logisim

A gate-level implementation of a **RISC-V Multicycle Control Unit** designed using Logisim. This project demonstrates how digital logic gates decode control conditions and generate processor control signals for coordinating datapath operations.

## Control Signals

| Signal | Description |
|---|---|
| `PCWrite` | Enables program counter update |
| `PCWriteCond` | Controls conditional PC updates |
| `PCSource` | Selects the next PC source |
| `IorD` | Selects the memory address source |
| `MemRead` | Enables memory read |
| `MemWrite` | Enables memory write |
| `IRWrite` | Enables instruction register write |
| `RegWrite` | Enables register write-back |
| `SrcReg` | Source register selection control |
| `ALUOp1`, `ALUOp0` | ALU operation control bits |
| `ALUSrcA` | Selects the ALU first operand source |
| `ALUSrcB1`, `ALUSrcB0` | Selects the ALU second operand source |
| `clock` | Clock input |
| `enable` | Enable input |

*Note: The exact behaviour of each signal depends on the circuit wiring and the datapath connected to it.*

## Tools Used

- Logisim 2.7.1
- Digital Logic Design
- Computer Architecture

## Repository Structure

```text
RISC-V-Multicycle-Control-Unit-Logisim/
├── RISC-V Multicycle Control Unit(1).circ
├── README.md
└── images/
    └── control-unit.png
```

The `images/control-unit.png` file is optional. Add a screenshot of your actual circuit to display it in this README.

## Author

**Saim Naveed**

Computer Systems Engineering | Digital Logic Design | Computer Architecture

---

If you find this project useful for learning digital logic and computer architecture, consider giving the repository a star!


