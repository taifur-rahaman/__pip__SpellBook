
# PiP SpellBook

A personal collection of Python packages that I find useful and want to keep track of for future projects.  
This repository serves as a simple reference list, making it easy to revisit helpful modules without searching for them again.

---

## 📚 Purpose

The goal of **PiP SpellBook** is to maintain a curated list of Python packages along with short notes, version references, and installation commands.  
Each entry is something I found helpful, interesting, or worth exploring later.

---

## 📦 Stored Packages

### **English-Dictionary**
  In-memory dictionary of 100 thousand English words.
  - **Version:** 1.0.24 (Released: Jul 26, 2021)
  - **Installation:**
    ```python
    pip install english-dictionary
    ```
  - **Usage:**
  ```python
    from english_dictionary.scripts.read_pickle import get_dict
    english_dict = get_dict()
    english_dict["xylophone"]  # english_dict is a Python dictionary of English
  ```
