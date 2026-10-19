# Module 1: Why We Program (Chapter One, part 1)

## Why Program
- Computers always ask: "What next?"
- Programmers serve the user. Software is the bridge between the hardware and the user.
- Programmers use programming languages (Python), interpreters, compilers and networks.
- Computer = hardware + software
  - Hardware = the physical parts (CPU, memory, keyboard, screen)
  - Software = any set of instructions (my Python programs, but also Chrome, VS Code, macOS)
- Program = a sequence of exact instructions, step by step
  - Example: a dance. While the music is playing: left hand out, right hand out, wiggle, wiggle, jump.
- Instructions must be typed correctly: "right ham" instead of "right hand" -> syntax error. The computer doesn't know what to do.
- The computer can't fix errors by itself, unlike our brain. It does exactly what I wrote.
  If the result is wrong, the mistake is in the instructions.
- Computers are great at repetitive, boring tasks (e.g. counting words in a text): very fast, never tired or bored.

## Hardware Overview
- Generic computer (all hardware): input/output devices <-> CPU <-> main memory, plus secondary memory
- I/O devices: mouse, keyboard, screen
- CPU: runs instructions very fast and always asks "What next?"
  It is fast, not intelligent: it only follows instructions. CPUs are much smaller today than in the 1960s.
- Main memory (RAM): fast, close to the CPU, holds what is being used right now, emptied when the computer turns off
- Secondary memory (SSD / hard drive): slower, holds a lot, keeps everything even when the computer is off
- Who answers "What next?" -> the PROGRAMMER, in advance, by writing the instructions

### The chain
Programmer writes instructions -> saved in secondary memory -> copied into main memory -> CPU reads them one by one, very fast
- Python code is translated into machine language (0s and 1s), because that is the only language the CPU understands.
- Running a .py file copies it into RAM; the file stays on the SSD.
  The Python interpreter and open apps (VS Code, Jupyter, Terminal) also run in RAM.

### Kitchen analogy
- Cook = CPU (fast, but only follows instructions)
- Recipe = program (written by the programmer)
- Box near the stove = main memory (RAM)
- Refrigerator = secondary memory (SSD)
- Customer's order = input (like the keyboard)

### Why save often
- Unsaved changes live only in RAM. If the power goes off, they are lost.
  The last saved version is still safe on the SSD.
- Cmd+S copies my changes to the SSD. git push = an extra backup on GitHub.

## Python as a Language
- Dr. Chuck compares Python to Parseltongue from Harry Potter: a language most people don't understand (yet).
- Created by Guido van Rossum
- A good first language: powerful, useful, easy to learn
- Syntax error = Python is lost: it doesn't understand what I wrote. Python can't guess, so I have to fix it.