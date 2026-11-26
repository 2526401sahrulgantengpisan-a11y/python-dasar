# Basic Python Project (`proyek-python-dasar`)

This repository contains a collection of practice scripts and learning documentation covering fundamental to intermediate Python programming concepts, including Object-Oriented Programming (OOP), file handling, modules, and custom packages.

## 📂 Project Structure

```text
proyek-python-dasar/
├── python-dasar/
│   ├── my_package/            # Custom Python package directory
│   │   ├── __init__.py        # Package initialization file
│   │   ├── geometri.py        # Geometry calculation module (e.g., luas_persegi)
│   │   └── operasi.py         # Basic arithmetic operations module (e.g., kurang)
│   ├── hello.py               # Basic syntax and Hello World output
│   ├── struktur-dasar.py      # Fundamental Python code structure
│   ├── variable.py            # Variable declaration and assignment
│   ├── constants.py           # Constants implementation
│   ├── tipe-data.py           # Built-in Python data types
│   ├── operator.py            # Arithmetic, comparison, and logical operators
│   ├── control-flow.py        # Conditional statements and loops
│   ├── list.py                # List data structure and methods
│   ├── dictionary.py          # Dictionary data structure (key-value pairs)
│   ├── function.py            # Defining and calling functions
│   ├── matematika.py          # Custom math helper module
│   ├── module.py              # Importing and using modules
│   ├── pakage.py              # Importing custom packages and built-in modules (os, datetime)
│   ├── file-handling.py       # Reading and writing external text files
│   ├── contoh.txt             # Sample text file for file handling exercises
│   ├── data.txt               # Data text file for I/O operations
│   ├── exeption.py            # Error and exception handling (try-except)
│   ├── class.py               # OOP basics: Classes and Objects
│   ├── iheritance.py          # OOP: Inheritance
│   ├── polymorphism.py        # OOP: Polymorphism
│   ├── encapsulation.py       # OOP: Encapsulation (access modifiers)
│   └── abstraction.py         # OOP: Abstraction
├── screenshot/                # Execution outputs and documentation screenshots
├── venv/                      # Python virtual environment
├── .gitignore                 # Files and directories ignored by Git
├── README.md                  # Project documentation
└── requirements.txt           # Python dependencies list
```

## 📚 Topics Covered

1. **Python Fundamentals (`hello.py`, `struktur-dasar.py`, `variable.py`, `constants.py`, `tipe-data.py`, `operator.py`)**: Core syntax, variables, constants, data types, and operators.
2. **Control Flow (`control-flow.py`)**: Conditional branching and iteration logic.
3. **Data Structures (`list.py`, `dictionary.py`)**: Storing and manipulating collections of data.
4. **Functions (`function.py`)**: Writing reusable blocks of code.
5. **Modules & Packages (`matematika.py`, `module.py`, `pakage.py`, `my_package/`)**: Organizing code into reusable modules and packages, as well as utilizing built-in modules like `os` and `datetime`.
6. **File Handling & Exception Handling (`file-handling.py`, `exeption.py`)**: Performing file I/O operations on `.txt` files and handling runtime errors gracefully.
7. **Object-Oriented Programming (`class.py`, `iheritance.py`, `polymorphism.py`, `encapsulation.py`, `abstraction.py`)**: Applying core OOP principles in Python.

## 🚀 Getting Started

1. **Clone the repository** (or navigate to your local project folder):
   ```bash
   cd proyek-python-dasar
   ```

2. **Activate the Virtual Environment**:
   * **Windows (PowerShell):**
     ```powershell
     .\venv\Scripts\Activate.ps1
     ```
   * **Linux/macOS:**
     ```bash
     source venv/bin/activate
     ```

3. **Install dependencies** (if any):
   ```bash
   pip install -r requirements.txt
   ```

4. **Run a Python script**:
   ```bash
   python python-dasar/pakage.py
   ```