# 0x07. Python - Test-driven development

## General
* Why Python programming is awesome
* What’s an interactive test
* Why tests are important
* How to write Docstrings to create tests
* How to write documentation for each module and function
* What are the basic option flags to create tests
* How to find edge cases

## Requirements
### Python Scripts

* Allowed editors: vi, vim, emacs
* All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)
* All your files should end with a new line
* The first line of all your files should be exactly #!/usr/bin/python3
* A README.md file, at the root of the folder of the project, is mandatory
* Your code should use the pycodestyle (version 2.8.*)
* All your files must be executable
* The length of your files will be tested using wc

### Python Test Cases

* Allowed editors: vi, vim, emacs
* All your files should end with a new line
* All your test files should be inside a folder tests
* All your test files should be text files (extension: .txt)
* All your tests should be executed by using this command: python3 -m doctest ./tests/*
* All your modules should have a documentation (python3 -c 'print(__import__("my_module").__doc__)')
* All your functions should have a documentation (python3 -c 'print(__import__("my_module").my_function.__doc__)')
** A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of it will be verified)
* We strongly encourage you to work together on test cases, so that you don’t miss any edge case – The Checker is checking for tests!

## Tasks
| Filename | Description |
| -------- | ----------- |
| `0-add_integer.py` | Function that adds two integers (Doctest on `tests/0-add_integer.txt`) |
| `2-matrix_divided.py` | Function that divides all elemtns of a matrix (Doctest on `tests/2-matrix_divided.txt`) |
| `3-say_my_name.py` | Function that prints `My name is <first name> <last name>` (Doctest on `tests/3-say_my_name.txt`) |
| `4-print_square.py` | Function that prints a square with the character `#` (Doctest on `tests/4-print_sqaure.txt`) |
| `5-text_indentation.py` | Function that prints a text with 2 new lines after each of these `.`, `?` and `:` (Doctest on `tests/5-text_indentation.txt`) |
| `tests/6-max_integer_test.py` | Unittests for the function `def max_integer(list=[])` |
| `100-matrix_mul.py` | Function that multiplies 2 matrices (Doctest on `tests/100-matrix_mul.txt`) |
| `101-lazy_matrix_mul.py` | Function that multiplies 2 matrices by using the module **NumPy** (Doctest on `tests/101-lazy_matrix_mul.txt`) |
| `102-python.c` | Function that prints Python strings |
