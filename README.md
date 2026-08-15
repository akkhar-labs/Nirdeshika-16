# Nirdeshika-16 — A Computer Processor That Understands Bengali

**Nirdeshika-16** is a computer processor design that works entirely in Bengali. Not translated into Bengali. Built from scratch using Bengali language, numbers, and logic.

> **For hardware engineers and architects:** This repository is the technical specification of the Nirdeshika-16 processor. If you want to write and run Bengali programs, head over to the [Shimu](https://github.com/Akkhar-Labs/Shimu) (simulator) and [Boyon](https://github.com/Akkhar-Labs/Boyon) (assembler) repositories instead.

> **What you can do with it right now:** Write programs in Bengali. Assemble them into machine code. Run them on a virtual CPU. All in Bengali. No English required.

---

## What This Actually Means

Every computer processor executes binary — patterns of 0s and 1s. But the human-facing layer — the instruction mnemonics, register names, documentation, and encoding — is what engineers actually read and write. For decades, that human-facing layer has been English. Intel's instruction set is English. ARM's instruction set is English. Even processors designed in China, Russia, and India use English at the human level.

Nirdeshika-16 is different. At the hardware level, it still runs on binary like any processor. But its human-facing layer — the commands, numbers, registers, and documentation — is entirely Bengali. Its commands are Bengali words. Its numbers use Bengali letters. Its internal logic follows Bengali conventions. You can write programs for it without knowing a single word of English.

---

## How It Works

A processor does three things: it takes instructions, processes them, and produces output. Nirdeshika-16 does all three in Bengali.

| What You Want To Do | How Nirdeshika-16 Handles It |
|---------------------|-------------------------------|
| **Write a program** | Use Bengali words as commands. No English keywords. |
| **Store numbers** | Use Bengali consonants for values beyond 9. A custom number system called Akkhar-Hex. |
| **Process text** | Uses a planned custom encoding (Akshar-Lipi 8) designed specifically for Bengali. |
| **Run the program** | The simulator (Shimu) executes it like a real CPU, showing you exactly what happens. |

---

## What You Can Build With It

- **Learn how computers actually work** — by seeing one that speaks your language
- **Write simple programs** — math calculations, logic operations, data movement
- **Understand assembly language** — without the English barrier
- **Teach computing** — in Bengali classrooms, without switching to English for technical terms

---

## What's Included

You get three things when you download Nirdeshika-16:

1. **The Processor Design** — Complete specification. Every instruction. Every register. Every rule. Fully documented.
2. **The Assembler (Boyon)** — A tool that converts Bengali programs into machine code the processor can run.
3. **The Simulator (Shimu)** — A virtual CPU that runs your Bengali programs on any computer, showing you exactly how the processor works internally.

---

## Technical Details (For Those Who Want Them)

| Specification | Value |
|---------------|-------|
| **Processor Type** | 16-bit |
| **Design Style** | RISC (simple, fast instructions) |
| **Instruction Format** | Fixed 16-bit length. 4 bits for the command, 4 bits for which register, 8 bits for data. |
| **Number of Instructions** | 16 unique commands |
| **Number of Registers** | 16 storage locations inside the processor |
| **Memory** | 64KB of virtual RAM (in the simulator) |
| **Number System** | Akkhar-Hex (Bengali consonants represent numbers 10 through 15) |
| **Character Encoding** | Akshar-Lipi 8 (planned — custom encoding for Bengali text) |

---

## The Bigger Picture

Nirdeshika-16 is the first piece of a larger plan: a complete computer system where everything works in Bengali.

- **Nirdeshika-64** — A more powerful 64-bit processor (coming next)
- **Kotha** — A Bengali programming language where you write code in Bengali sentences
- **BAPS** — A kernel (the core of an operating system) written in Bengali
- **Matrika OS** — A complete operating system in Bengali
- **AKFS** — A file system for storing data, designed in Bengali

The goal is simple: a computer that speaks your language. From the moment you turn it on to the moment you write a program. No English. No translation. Just Bengali.

---

## Who Built This

**Rahat Hasan** — A systems architect from Bogura, Bangladesh who designed Nirdeshika-16 from first principles. He designed the Akkhar-Hex number system, the Akshar-Lipi 8 character encoding (planned), and the full instruction set architecture that enables Bengali speakers to program computers in their own language.

**Akkhar-Labs** — A research collective building sovereign computing technology for Bangladesh. Nirdeshika-16 is the foundation of a larger vision: a complete Bengali-language computing stack, from silicon to operating system, where no English is required at any layer.

---

## Get Started

Everything is free and open source. Download the specification, the assembler, and the simulator from the links above. Write your first Bengali program today.

No English required.