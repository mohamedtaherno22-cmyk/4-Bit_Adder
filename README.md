# 4-Bit_Adder
A 4-bit adder built entirely from discrete transistors and resistors. The project explores digital logic at the hardware level, combining 30 NOR Gates and 1 AND gate to form 3 full adders and 1 half adder. Everything is assembled onto a custom 8cm x 7cm PCB. You can extend the circuit beyond 4 bits by adding more full-adders, allowing it to handle higher binary addition. Each additional stage uses the carry-out from the previous stage as its carry-in (Ci).

## Features

- **4-Bit Binary Adder:** Adds two 4-bit binary numbers using a transistor-based logic circuit.
- **LED Output Indicators:** LEDs display the resulting binary sum and the carry-out, for an easy-to-read output.
- **Switch-Controlled Inputs:** Allows users to manually set the binary inputs and test different addition combinations.
- **Compact PCB Design:** The entire circuit is assembled onto a double-layered 8 × 7.5 cm PCB.

## Hardware

- **31 NPN Transistors:** make up the logic gates that make up the adder.
- **Resistors:** Includes 5 × 220Ω (for LEDs ouput), 60 × 10kΩ (Handle the transistor input), and 30 × 4.7kΩ pull-up resistors.
- **5 LEDs:** Used to display the binary output bits and the final carry.
- **8 Switches:** Used to manually set the input bits for the two binary numbers.
- **PCB (can be replaced by breadboards)**

## Schematics
**AND_Gate & NOR_GATE**

<img width="335" height="443" alt="eeschema_CMD7S04vdq" src="https://github.com/user-attachments/assets/9354c23a-ffa3-4583-a557-ffec9d34775a" />
<img width="410" height="443" alt="image" src="https://github.com/user-attachments/assets/a7cd1771-84d1-4699-8c74-3683598d0bf9" />

**Half-Adder (2-Bit Adder)**

<img width="668" height="344" alt="eeschema_zgTw1CkZoF" src="https://github.com/user-attachments/assets/c2caeedb-c915-4ebc-a12f-d30eceb17ea9" />

**Full-Adder (3-Bit Adder)**

<img width="1091" height="399" alt="eeschema_jYQ8fFtcT1" src="https://github.com/user-attachments/assets/a8d595c7-7f36-41f9-8b57-4f120b5c4262" />

**Schematic**
<img width="1832" height="695" alt="image" src="https://github.com/user-attachments/assets/67f04735-7a19-48d2-8d84-b74b7894a4ae" />

## PCB
<img width="1568" height="817" alt="image" src="https://github.com/user-attachments/assets/1ef58f6c-0c2b-4ddb-8851-e7126bdc717a" />

<img width="1896" height="709" alt="image" src="https://github.com/user-attachments/assets/e354879b-7434-44b3-831f-ce930add2d8c" />

## 3D Model

<img width="1675" height="895" alt="image" src="https://github.com/user-attachments/assets/6a966a05-9e88-4734-b8d2-26e8eb8b1d93" />

