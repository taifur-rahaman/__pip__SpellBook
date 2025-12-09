
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

### **PyCountry**
  Pycountry provides the ISO databases for the standards for country names, currencies, and languages.
```markdown
  - 639-3 Languages
  - 3166 Codes for representation of names of countries and their subdivisions
  - 3166-1 Countries ***(I just Used this one)***
  - 3166-3 Deleted countries 
  - 3166-2 Subdivisions of countries 
  - 4217 Currencies 
  - 15924 Scripts
```
- Version: 24.6.1 (Released: Jun 01, 2024)

- Installation:
  ```python
  pip install pycountry
  ```

- Usage:
  ```python
  from pycountry import countries
  for country in countries:
      print(country.name)
  ```