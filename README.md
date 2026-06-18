# Nirdeshika-16 — The World's First Bengali Instruction Set Architecture

**Nirdeshika-16** is a 16-bit **Instruction Set Architecture (ISA)** designed
and implemented by **Akkhar-Labs**. It is the first computing architecture to
use Bengali linguistic and mathematical conventions as its native design
language — from custom encoding to instruction logic.

> **Status:** Reference Implementation (Feature-Complete)  
> **Successor:** Nirdeshika-64 (Planned)

---

## Purpose

Nirdeshika-16 exists to answer a foundational question:

> _"Can a complete Instruction Set Architecture be designed natively in Bengali,
> without depending on English-centric computing standards?"_

The answer is **yes**. Nirdeshika-16 demonstrates this through:

- Custom **Akshar-Lipi 8** character encoding
- Proprietary **Akkhar-Hex** number system (Bengali consonants for hexadecimal
  values)
- Bengali-named registers, opcodes, and addressing modes
- A working assembler and virtual simulator

---

## Key Technical Specifications

| Property          | Specification                                    |
| ----------------- | ------------------------------------------------ |
| **Architecture**  | 16-bit Native                                    |
| **Design Type**   | Load-Store (RISC)                                |
| **Endianness**    | Little-Endian                                    |
| **Encoding**      | Akshar-Lipi 8 (Custom)                           |
| **Number System** | Akkhar-Hex (Bengali consonants for values 10–15) |

---

## Instruction Format (4-4-8)

Every instruction is 16 bits wide and follows a fixed **4-4-8** structure:

| Field                   | Width  | Description                                      |
| ----------------------- | ------ | ------------------------------------------------ |
| **Opcode**              | 4 bits | 16 unique instructions                           |
| **Register ID**         | 4 bits | 16 general-purpose and special-purpose registers |
| **Immediate / Address** | 8 bits | Constant value or memory address                 |

This RISC-style, fixed-width format ensures deterministic decoding.

---

## Ecosystem

The reference implementation includes two supporting tools:

- **[Boyon (Assembler)](https://github.com/Akkhar-Labs/Boyon):** A native
  assembler that processes Bengali-syntax assembly code into Nirdeshika-16
  binary output.
- **[Shimu (Simulator)](https://github.com/Akkhar-Labs/Shimu):** A
  high-performance virtual CPU simulator implementing the full
  fetch-decode-execute cycle with 64KB of virtual RAM.

---

## Documentation

The complete technical specification is available in the
**[Master Specification PDF](https://github.com/Akkhar-Labs/Nirdeshika-16/releases)**.

---

## Roadmap

Nirdeshika-16 is feature-complete. The next iteration — **Nirdeshika-64** — will
be a production-grade 64-bit architecture as part of the broader **Sovereign
Bengali Computing Stack**:

- **Matrika OS** — Native operating system
- **BAPS Kernel** — Bengali-native kernel
- **Kotha Language** — Conversational Bengali programming language

---

## Architecture & Authorship

- **Architect:** [Rahat Hasan](https://github.com/rahatarch)
- **Organization:** [Akkhar-Labs](https://github.com/Akkhar-Labs)

---

## License

This project is open source. See [LICENSE](LICENSE) for details.
