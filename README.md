# CUSTOM-INSTRUCTIO-COMPILER
# Arithmetic Expression Compiler

This project is a Python-based compiler that parses and evaluates arithmetic expressions. It generates:

- ✅ Tokens from the input
- 🧠 Abstract Syntax Tree (AST)
- 🧾 Three Address Code (TAC)
- 📊 Final evaluated result

---
## 🚀 How to Run

### Prerequisites

Ensure you have **Python 3** installed on your system.

### Steps

1. Extract the ZIP.
2. Open terminal in the project folder.
3. Run the following command:

```bash
python3 main.py
```

---

## ✅ Example Output

Here’s an example for the input expression:

```plaintext
(A * B) + (C * D) + E
```

**Output:**

```plaintext
TOKENS:
  A = 4.0
  B = 5.0
  C = 2.0
  D = 2.0
  E = 3.0

INTERMEDIATE CODE (TAC):
  t1 = 4.0 * 5.0
  t2 = 2.0 * 2.0
  t3 = t2 + 3.0
  t4 = t1 + t3

RESULT:
  27.0
```

---

## 📁 Project Structure

```
.
├── main.py                   # Main driver script
├── lexer.py                  # Tokenizer
├── syntax_analysis.py        # AST generation
├── semantic_analysis.py      # Expression evaluation
├── intermediate_code.py      # TAC generation
├── code_generation.py        # Result evaluation
├── output.txt                # Output file
├── output_screenshot.png     # Sample output screenshot
└── README.md                 # This file
```

---



---

## 📜 License

MIT License – feel free to use, modify, and enhance.
