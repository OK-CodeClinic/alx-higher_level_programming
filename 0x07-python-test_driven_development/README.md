# Python - Test-driven development

### **General Knowledge**
**In this project, i started learning;**
1. Why Python programming is awesome
2. What’s an interactive test
3. Why tests are important
4. How to write Docstrings to create tests
5. How to write documentation for each module and function
6. What are the basic option flags to create tests
7. How to find edge cases

## Author

- [Kehinde Omokungbe](https://www.github.com/OK-CodeClinic)
## Requirements
### Python Scripts
- Allowed editors: vi, vim, emacs
- All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)
- All your files should end with a new line
- The first line of all your files should be exactly #!/usr/bin/python3
- A README.md file, at the root of the folder of the project, is mandatory
- Your code should use the pycodestyle (version 2.8.*)
- All your files must be executable
- The length of your files will be tested using wc

### Python Test Cases
- Allowed editors: vi, vim, emacs
- All your files should end with a new line
- All your test files should be inside a folder ```tests```
- All your test files should be text files (extension:``` .txt```)
All your tests should be executed by using this command: ```python3 -m doctest ./tests/*```
All your modules should have a documentation ```(python3 -c 'print(__import__("my_module").__doc__)')```
All your functions should have a documentation ```(python3 -c 'print(__import__("my_module").my_function.__doc__)')```
A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of it will be verified)
We strongly encourage you to work together on test cases, so that you don’t miss any edge case – The Checker is checking for tests!
## Tasks

#### **Mandatory Tasks**

* **0. Integers addition**
  * [0-add_integer.py](./0-add_integer.py): Python function that returns the integer addition of two numbers.
  * If either of `a` or `b` is not an `int` or `float`, a `TypeError` is raised with the message `a must be an integer` or `b must be an integer`.
  * If either of `a` or `b` is a `float`, it is casted to an `int` before addition.

* **1. Divide a matrix**
  * [2-matrix_divided.py](./2-matrix_divided.py): Python function that divides all elements of a matrix by a common divisor.
  * Returns a new matrix representing the division of all elements of `matrix` by `div`.
  * Quotients are rounded to two decimal places.
  * If `matrix` is not a list of lists of `int`s or `float`s, a `TypeError` is raised with the message `matrix must be a matrix (list of lists) of integers/floats`.
  * If `matrix` contains rows of different lengths, a `TypeError` is raised with the message `Each row of the matrix must have the same size`.
  * If the divisor `div` is not an `int` or `float`, a `TypeError` is raised with the message `div must be a number`.
  * If `div` is `0`, a `ZeroDivisionError` is raised with the message `division by zero`.

* **2. Say my name**
  * [3-say_my_name.py](./3-say_my_name.py): Python function that prints a name in the format `My name is <first_name> <last_name>`.
  * If either of `first_name` or `last_name` is not a `str`, a `TypeError` is raised with the message `first_name must be a string` or `last_name must be a string`.

* **3. Print square**
  * [4-print_square.py](./4-print_square.py): Python function that prints a square using the `#` character.
  * The paramter `size` represents the height/width of the square.
  * If `size` is not an `int`, a `TypeError` is raised  with the message, `size must be an integer`.
  * If `size` is less than `0`, a `ValueError` is raised with the message `size must be >= 0`.

* **4. Text indentation**
  * [5-text_indentation.py](./5-text_indentation.py): Python function that prints text with indentation.
  * Two new lines are printed after any `.`, `?`, or `:` character.
  * If `text` is not a `str`, a `TypeError` is raised with the message `text must be a string`.
  * No spaces are printed at the beginning or end of each printed line.

* **5. Max integer - Unittest**
  * [tests/6-max_integer_test.py](./tests/6-max_integer_text.py): Python class/script that runs unittests for the function `def max_integer(list=[]):` (provided by ALX School of Software Engineering).

#### **Advanced Tasks**

* **6. Matrix multiplication**
  * [100-matrix_mul.py](./100-matrix_mul.py): Python function that multiplies two matrices.
  * Returns a new matrix representing the multiplication of `m_a` by `m_b`.
  * If either of `m_a` or `m_b` is empty (ie. `== []` or `== [[]]`), a `ValueError` is raised with the message `m_a can't be empty` or `m_b can't be empty`.
  * If either of `m_a` or `m_b` is not a list, a `TypeError` is raised with the message `m_a must be a list` or `m_b` must be a list.
  * If either of `m_a` or `m_b` is not a list of lists, a `TypeError` is raised with the message `m_a must be a list of lists` or `m_b must be a list of lists`.
  * If either of `m_a` or `m_b` is not a list of lists of `int`s or `float`s, a `TypeError` is raised with the message `m_a should contain only integers or floats` or `m_b should contain only integers or floats`.
  * If either of `m_a` or `m_b` contains rows of different lengths, a `TypeError` is raised with the message `each row of m_a must should be of the same size` or `each row of m_b must should be of the same size`.
  * If `m_a` and `m_b` cannot be multiplied (ie. row size of `m_a` does not match column size of `m_b`), a `ValueError` is raised with the message `m_a and m_b can't be multiplied`.

* **7. Lazy matrix multiplication**
  * [101-lazy_matrix_mul.py](./101-lazy_matrix_mul.py): Python function that multiplies two matrices using the module `NumPy`.
  * Identical in function to [100-matrix_mul.py](./100-matrix_mul.py).

* **8. CPython #3: Python Strings**
  * [102-python.c](./102-python.c): C function that prints basic information about Python string objects.
![Logo](https://i0.wp.com/aceworldpub.com.ng/wp-content/uploads/2022/03/unnamed.png?resize=880%2C528&ssl=1)
