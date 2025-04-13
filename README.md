# TokenizeC - Mini C Compiler

**TokenizeC** is a lightweight compiler for a subset of the C programming language, developed as part of the **Compiler Design Lab Course (TCS601)**. The project is structured into four incremental phases, each focusing on a core component of compiler design—from lexical analysis to intermediate code generation.

---

## 📌 Project Overview

This mini compiler demonstrates the key stages of compilation, using widely accepted compiler construction tools such as **Lex** and **Yacc**. It is designed to tokenize, parse, and analyze a simplified version of C code and generate intermediate code suitable for further optimization or execution.

---

## 📂 Phases and Objectives

| Phase     | Objective                                                                                      |
|-----------|------------------------------------------------------------------------------------------------|
| Project-1 | Develop a **Lexical Analyzer** using Lex to tokenize input code for a subset of the C language |
| Project-2 | Build a **Parser** using Yacc to process tokens and validate syntax based on CFG rules         |
| Project-3 | Implement a **Semantic Analyzer** to ensure meaningful and context-aware code translation      |
| Project-4 | Create an **Intermediate Code Generator** for converting validated code into intermediate form |

---

## ⚙️ Tools and Technologies

- **Lex** – For lexical analysis  
- **Yacc** – For syntax analysis  
- **C Language** – Core language for compiler logic  
- **Makefile** – For streamlined compilation

---

## 👥 Team Members

- **Abhishek Agrawal** (220111249)  
- **Dhrve Sahdev** (22021842)  
- **Shaurya Bhardwaj** (220112851)

---

## 📁 Repository Structure
<pre>TokenizeC
├──  Poject-1
│   ├── lexer.l
│   ├── input.c
│   └── Readme.md
├── Project-2/
│   ├── parser.y
│   ├── lexer.l
│   └── Readme.md
├── Project-3/
│   └── semantic.c
|   └── Reade.md
├── Project-4/
│   └── icg.c
|   └── Readme.md
├── README.md
└── sample_programs/
    ├── example1.c
    └── example2.c  </pre> 
