# python_piscine

# Python 42: Module 00 - Foundations

This initial module establishes the core principles of professional Python development, focusing on clean syntax, environment configuration, and basic control logic.

---

## 1. Environment Configuration
Before writing any logic, an industry-standard workflow was established:
* **Interpreter:** Utilization of Python 3.10+ for modern features and *Type Hinting*.
* **Linting (Flake8):** Implementation of **PEP8** rules to ensure readable code (standardized spacing, blank lines, and line length).
* **Virtual Environments (`venv`):** Dependency isolation to prevent conflicts between different project modules.
* **Directory Structure:** Strict organization by exercises (`ex00` to `ex07`) following the 42 School hierarchy.

---

## 2. Core Programming Concepts
Through 8 exercises (`ex00` to `ex07`), the following pillars were mastered:

### **Syntax & Structure**
* **Modularity:** Use of the `if __name__ == "__main__":` block to allow code reuse without accidental execution.
* **Documentation:** Mandatory implementation of *Docstrings* in modules and functions.
* **Type Hinting:** Explicit definition of data types (`str`, `int`, `-> None`) for robust and self-documenting code.

### **Input/Output (I/O)**
* **Data Capture:** Using `input()` combined with string normalization (`.lower()`, `.capitalize()`).
* **Type Casting:** Secure conversion of data types (e.g., `int(input())`).
* **f-strings:** Modern and dynamic string formatting for clean console output.

### **Control Flow**
* **Conditionals:** Mastery of `if / elif / else` structures for decision making.
* **Iteration:** Understanding the difference between `while` loops (manual control) and `for` loops with `range()` (automatic iteration).
* **Recursion:** Implementation of self-calling functions (Head vs. Tail recursion) to manage the call stack effectively.

---

> **Project Status:** Module 00 successfully completed.
