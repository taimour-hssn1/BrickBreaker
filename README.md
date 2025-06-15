# 🧱 Brick Breaker (Intel 8086 - MASM)

A classic **Brick Breaker** game developed using **Intel 8086 Assembly Language** with **MASM**. This project runs in real mode and demonstrates low-level programming techniques for graphics, input handling, and game logic.

## 🎮 Features
- Paddle controlled with arrow keys
- Ball physics with basic collision detection
- Brick layout and scoring
- Game over and win screens

## 🛠️ Requirements
- DOSBox or any x86 emulator
- MASM assembler
- Linker (like TLINK)

## 🏃‍♂️ How to Run
1. Assemble the code(after you have mounted to the 8086 directory i.e. mount c c:/8086) :
   masm graphics.asm;
   
2. Link the object file:
   link graphics.obj
   
3. Run using DOSBox:
   graphics.exe or simply graphics

## 📸 Screenshots
![Screenshot 2025-06-15 215845](https://github.com/user-attachments/assets/d0dab569-b61a-40f2-b460-2437b2b0b18a)
![Screenshot 2025-06-15 215855](https://github.com/user-attachments/assets/f81ee371-bac2-429e-837e-4cfe9e90a164)

## 📚 Learning Outcomes
- Low-level graphics programming
- Interrupt-based keyboard handling
- Real-time logic using 8086 timers

## 🤝 Contributing
Feel free to fork and improve the game or optimize the assembly code!



