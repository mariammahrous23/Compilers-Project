# 🎀 Compilers-Project

A pastel-themed graphical compiler frontend built with **PyQt5**, featuring syntax and semantic analysis, quadruple code generation, and export capabilities.

---

## 🚀 How to Run the Project

### 📦 1. Install Dependencies

#### ✅ Frontend (Python GUI)

Make sure Python 3 is installed, then install the required packages:

```bash
pip install PyQt5 QScintilla
```

#### ✅ Backend (Compiler)

Install development tools:

```bash
sudo apt update
sudo apt install build-essential bison flex
```

---

### ⚙️ 2. Build the Compiler

```bash
make
```

This generates the `./compiler` binary used by the GUI.

---

### 💻 3. Run the GUI

```bash
python3 gui.py
```

This will launch the pastel-themed interface.

---

### 📤 4. Export Output Files

After clicking **Compile**, you can click **Export** to:

* Save:

  * `input_code.txt`
  * `symbol_table.txt`
  * `quadruples.txt`
  * `output.asm`
  * `syntax_errors.txt`
  * `semantic_errors.txt`
  * `warnings.txt`
* All files are saved to an `outputs/` folder

---

## 🌸 Features

* 💅 Beautiful, pastel-themed interface
* ✍️ Syntax & semantic error highlighting
* 📐 Quadruple code generation
* 📤 One-click export of all results

---

## 🧠 Developers

| Name   | Contribution                     |
| ------ | -------------------------------- |
| Mira   | Lexer, GUI, and Semantic Analyzer 💖    |
| Mimo   | Lexer, and Symbol Table 📚                 |
| Monmon | Parser, Syntax Errors, Type Conversions, and Quadruples 🌺 |
| Fofa   | Parser, Syntax Errors, Type Conversions, and Quadruples 🧮 |

---

## 🖼 Screenshot 
![image](https://github.com/user-attachments/assets/175ac7e9-a5ab-45d5-83ab-5d997e188b32)

