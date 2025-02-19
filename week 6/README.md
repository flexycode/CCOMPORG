<!-- Background github cover with short introduction down below -->
<img src="https://github.com/flexycode/CCOMPORG/blob/main/assets/asset1.jpg" />

# 💫 CCOMPORG - COMPUTER ORGANIZATION AND ARCHITECTURE

### Name: [Jay Arre Talosig](https://github.com/flexycode)  
### Subject & Section: [CCOMPORG - COM231](https://www.geeksforgeeks.org/computer-organization-and-architecture-tutorials/)
### Professor: Jay Abaleta      
### No. of Units: 3 Units
### Prerequisite: [CCOBJPGL - Object Oriented Programming](https://github.com/flexycode/CCOBJPGL-JAVA)

# 🧠 Overview

The course covers the general introduction to the computer organization and architecture concept. The key concepts on RISC-based instruction set, pipeline and pipeline
hazard, performance measure, and Amdahl’s law will be discussed. It also covers design issues of computer architecture, specifically set design and instruction level parallelism.

## 🧠 Logic Gates and Breadboard Prototyping

## Overview

Logic gates are the fundamental building blocks of digital circuits. They perform basic logical functions essential for digital computing and electronic systems. Each logic gate corresponds to a specific logical operation, and they can be combined to create complex circuits.

## Basic Logic Gates

### 1. AND Gate
- **Symbol**: 
- **Truth Table**:

| A | B | Output (A AND B) |
|---|---|------------------|
| 0 | 0 | 0                |
| 0 | 1 | 0                |
| 1 | 0 | 0                |
| 1 | 1 | 1                |

### 2. OR Gate
- **Symbol**: 
- **Truth Table**:

| A | B | Output (A OR B) |
|---|---|-----------------|
| 0 | 0 | 0               |
| 0 | 1 | 1               |
| 1 | 0 | 1               |
| 1 | 1 | 1               |

### 3. NOT Gate
- **Symbol**: 
- **Truth Table**:

| A | Output (NOT A) |
|---|----------------|
| 0 | 1              |
| 1 | 0              |

### 4. NAND Gate
- **Symbol**: 
- **Truth Table**:

| A | B | Output (A NAND B) |
|---|---|-------------------|
| 0 | 0 | 1                 |
| 0 | 1 | 1                 |
| 1 | 0 | 1                 |
| 1 | 1 | 0                 |

### 5. NOR Gate
- **Symbol**: 
- **Truth Table**:

| A | B | Output (A NOR B) |
|---|---|------------------|
| 0 | 0 | 1                |
| 0 | 1 | 0                |
| 1 | 0 | 0                |
| 1 | 1 | 0                |

### 6. XOR Gate
- **Symbol**: 
- **Truth Table**:

| A | B | Output (A XOR B) |
|---|---|------------------|
| 0 | 0 | 0                |
| 0 | 1 | 1                |
| 1 | 0 | 1                |
| 1 | 1 | 0                |

### 7. XNOR Gate
- **Symbol**: 
- **Truth Table**:

| A | B | Output (A XNOR B) |
|---|---|-------------------|
| 0 | 0 | 1                 |
| 0 | 1 | 0                 |
| 1 | 0 | 0                 |
| 1 | 1 | 1                 |

## Understanding Logic Gates with a Breadboard

A breadboard is a reusable platform for prototyping electronic circuits without soldering. Here’s how to use a breadboard to understand logic gates:

### Materials Needed
- Breadboard
- Logic gate ICs (e.g., 7408 for AND gates, 7432 for OR gates, 7404 for NOT gates, etc.)
- LEDs (to visualize output)
- Resistors (typically 220Ω for LEDs)
- Power supply (5V is common for TTL logic)
- Jumper wires

### Steps to Build a Simple Logic Gate Circuit

1. **Power the Breadboard**: Connect the power supply to the breadboard. Typically, the top and bottom rows are used for power (positive and ground).

2. **Insert Logic Gate IC**: Place the logic gate IC on the breadboard. Ensure that it is oriented correctly (the notch or dot indicates pin 1).

3. **Connect Inputs**: Use jumper wires to connect the input pins of the logic gate to the power supply (5V for high, ground for low). For example, connect one input to 5V and the other to ground for an AND gate.

4. **Connect Outputs**: Connect the output pin of the logic gate to an LED (with a resistor in series) to visualize the output. Connect the other end of the LED to ground.

5. **Test the Circuit**: Change the input connections and observe the LED's behavior to understand how the logic gate operates.

## Conclusion

By using a breadboard to experiment with different logic gates, you can gain a practical understanding of how these fundamental components work in digital circuits. Happy prototyping!
