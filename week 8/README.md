<!-- Background github cover with short introduction down below -->
<img src="https://github.com/flexycode/CCOMPORG/blob/main/assets/asset1.jpg" />

# 💫 CCOMPORG - COMPUTER ORGANIZATION AND ARCHITECTURE

### Name: [Jay Arre Talosig](https://github.com/flexycode)  
### Subject & Section: [CCOMPORG - COM231](https://www.geeksforgeeks.org/computer-organization-and-architecture-tutorials/)
### Professor: Jay Abaleta      
### No. of Units: 3 Units
### Prerequisite: [CCOBJPGL - Object Oriented Programming](https://github.com/flexycode/CCOBJPGL-JAVA)

# 🧠 Logic Diagram 🛸

## 📜 Overview

Logic gates are the fundamental building blocks of digital circuits. They perform basic logical functions essential for digital computing and electronic systems. Each logic gate corresponds to a specific logical operation, and they can be combined to create complex circuits.

## 🧮 Logic Expression

The logic expression we will explore is:

**X = A (NOT B + NOT C) + A AND NOT B**

This expression can be broken down into the following components:
1. \( A \cdot (\overline{B} + \overline{C}) \)
2. \( A \cdot \overline{B} \)

## 🧊 Truth Table

Here is the truth table for the expression \( X = A (\overline{B} + \overline{C}) + A \cdot \overline{B} \):

| A | B | C | NOT B | NOT C | \(\overline{B} + \overline{C}\) | \(A \cdot (\overline{B} + \overline{C})\) | \(A \cdot \overline{B}\) | X |
|---|---|---|-------|-------|--------------------|--------------------|--------------|---|
| 0 | 0 | 0 |   1   |   1   |          1         |          0         |      0       | 0 |
| 0 | 0 | 1 |   1   |   0   |          1         |          0         |      0       | 0 |
| 0 | 1 | 0 |   0   |   1   |          1         |          0         |      0       | 0 |
| 0 | 1 | 1 |   0   |   0   |          0         |          0         |      0       | 0 |
| 1 | 0 | 0 |   1   |   1   |          1         |          1         |      1       | 1 |
| 1 | 0 | 1 |   1   |   0   |          1         |          1         |      1       | 1 |
| 1 | 1 | 0 |   0   |   1   |          1         |          1         |      0       | 1 |
| 1 | 1 | 1 |   0   |   0   |          0         |          0         |      0       | 0 |

## 💎 Logic Diagram

Below is the logic diagram representing the logic expression \( X = A (\overline{B} + \overline{C}) + A \cdot \overline{B} \):

```
      +---+       +---+       +---+
  A --|   |       |   |       |   |
      |AND|-------|OR |-------|   |
  B --|   |       |   |       |   |
      +---+       +---+       |   |
        |           |         |   |
        |           |         |   |
      +---+       +---+       |   |
  A --|   |       |   |       |   |
      |AND|       |NOT|       |   |
  B --|   |       |   |       |   |
      +---+       +---+       |   |
        |           |         |   |
        |           |         |   |
      +---+       +---+       |   |
  C --|   |       |   |       |   |
      |NOT|-------|   |       |   |
      +---+       |   |       |   |
                  +---+       |   |
                              +---+
```


### 🧠 Explanation of the Logic Diagram
1. **Inputs**: The inputs A, B, and C are shown on the left side of the diagram.
  
2. **NOT Gates**: 
   - The first NOT gate takes input B and produces \(\overline{B}\).
   - The second NOT gate takes input C and produces \(\overline{C}\).

3. **AND Gates**:
   - The first AND gate takes input A and the output of the OR gate (which combines \(\overline{B}\) and \(\overline{C}\)).
   - The second AND gate takes input A and the output of the first NOT gate (\(\overline{B}\)).

4. **OR Gate**:
   - The OR gate combines the outputs of the two NOT gates, producing \((\overline{B} + \overline{C})\).

5. **Final Output**:
   - The final output X is derived from the outputs of the two AND gates, indicating the result of the logical expression.

## 📈 Conclusion

This README provides an overview of the logic expression, its truth table, and a corresponding logic diagram. Understanding these components is essential for designing and analyzing digital circuits.
Happy prototyping!

## 🔭 Reference

#### ✨ Youtube Channel: 
- [Spanning Tree](https://www.youtube.com/watch?v=INEtYZqtjTo)
- [Computer Science Lessons](https://www.youtube.com/watch?v=BnB2m1nXZ84)
- [Mandy Elmore](https://www.youtube.com/@MandyTCTC)
- [Sebastian Lague](https://www.youtube.com/watch?v=I0-izyq6q5s)
- [Core Dumped](https://www.youtube.com/watch?v=HjneAhCy2N4)
  
Boolean Expressions to Circuits
- [Abelardo Pardo](https://www.youtube.com/watch?v=cblZ7Rdaxog)

#### ✨ Github:
- [SebLague](https://github.com/SebLague/Digital-Logic-Sim)


<!-- End point line insert Thanks for visiting enjoy your day, feel free to modify this  -->
---
<p align="center">
<img src="https://readme-typing-svg.demolab.com/?lines=Thanks+For+Visiting+Enjoy+Your+Day+~!;" alt="mystreak"/>
</p>

<!-- Genshin Impact -->
<div align="center">
<img src="https://media.giphy.com/media/qr4CNpxIL6wwNUYZsL/giphy.gif?cid=ecf05e47iqq0k4rx0kv1fb3w4hl8dja3ouiqzx4vz1665i6b&ep=v1_stickers_search&rid=giphy.gif&ct=s" width="300">
</div>

<!-- End point line insert Comeback again next time, feel free to modify this  -->
<p align="center">
<img src="https://readme-typing-svg.demolab.com/?lines=💎💎Come+Back+Again+next+time💎💎" alt="mystreak"/>
</p>

</p>
    
<br>
<!-- End point insert background effect line of sight color red -->
<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="1000">

