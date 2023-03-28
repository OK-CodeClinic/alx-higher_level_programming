# Python - Classes and Objects

### **General Knowledge**
**In this project, i started learning;**
1. Why Python programming is awesome
2. What is Object Oriented Programming (OOP)
3. “first-class everything”
4. What is a class
5. What is an object and an instance
6. What is the difference between a class and an object or instance
7. What is an attribute
8. What are and how to use public, protected and private attributes
9. What is ```self```
10. What is a method
11. What is the special ```__init__``` method and how to use it
12. What is Data Abstraction, Data Encapsulation, and Information Hiding
13. What is a property
14. What is the difference between an attribute and a property in Python
15. What is the Pythonic way to write getters and setters in Python
16. How to dynamically create arbitrary new attributes for existing instances of a class
17. How to bind attributes to object and classes
18. What is the ```__dict__``` of a class and/or instance of a class and what does it contain
19. How does Python find the attributes of an object or class
20. How to use the ```getattr``` function

## Author

- [Kehinde Omokungbe](https://www.github.com/OK-CodeClinic)
## General Requirements
- Allowed editors: vi, vim, emacs
- All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)
- All your files should end with a new line
- The first line of all your files should be exactly #!/usr/bin/python3
- A README.md file, at the root of the folder of the project, is mandatory
- Your code should use the pycodestyle (version 2.8.*)
- All your files must be executable
- The length of your files will be tested using wc
- All your modules should have a documentation (```python3 -c 'print(__import__("my_module").__doc__)```')
- All your classes should have a documentation (```python3 -c 'print(__import__("my_module").MyClass.__doc__)```')
- All your functions (inside and outside a class) should have a documentation (```python3 -c 'print(__import__("my_module").my_function.__doc__)```' and ```python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'```)
- A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of it will be verified)
## Tasks

#### **Mandatory Tasks**
* **0. My first square**
  * [0-square.py](./0-square.py): Python class `Square` that defines a square.

* **1. Square with size**
  * [1-square.py](./1-square.py): Python class `Square` that defines a square. Builds on
  [0-square.py](./0-square.py) with:
    * Private instance attribute `size`.
    * Instantiation with `size`.

* **2. Size validation**
  * [2-square.py](./2-square.py): Python class `Square` that defines a square. Builds on
  [1-square.py](./1-square.py) with:
    * Instantiation with optional `size`: `def __init__(self, size=0):`
  * If a provided `size` attribute is not an integer, a `TypeError` exception
  is raised with the message `must be an integer`.
  * If a provided `size` attribute is less than `0`, a `ValueError` exception
  is raised with the message `size must be >= 0`.

* **3. Area of a square**
  * [3-square.py](./3-square.py): Python class `Square` that defines a square. Builds on
  [2-square.py](./2-square.py) with:
    * Public instance attribute `def area(self):` that returns the current
    square area.

* **4. Access and update private attribute**
  * [4-square.py](./4-square.py): Python class `Square` that defines a square. Builds on
  [3-square.py](./3-square.py) with:
    * Property `def size(self):` to retrieve the private instance
    attribute `self`.
    * Property setter `def size(self, value):` to set `self`.

* **5. Printing a square**
  * [5-square.py](./5-square.py): Python class `Square` that defines a square. Builds on
  [4-square.py](./4-square.py) with:
    * Public instance method `def my_print(self):` that prints the square
    with the character `#` to standard output (if `size` == 0 -> prints an empty
    line).

* **6. Coordinates of a square**
  * [6-square.py](./6-square.py): Python class `Square` that defines a square. Builds on
  [5-square.py](./5-square.py) with:
    * Private instance attribute `position`.
    * Property `def position(self):` to retreive `position`.
    * Property setter `def position(self, value):` to set `position`.
    * Instantiation with optional `size` and `position`:
    `def __init__(self, size=0, position=(0, 0)):`
  * If a provided `position` attribute is not a tuple of two integers, a
  `TypeError` exception is raised with the message `position must be a tuple of
  2 positive integers`.

#### **Advanced Tasks**
* **7. Singly linked list**
  * [100-singly_linked_list.py](./100-singly_linked_list.py): Python classes `Node`
  and `SinglyLinkedList` that define a node of a singly-linked list and a singly-linked
  list. The class `Node` is defined with:
    * Private instance attribute `data`.
    * Property `def data(self):` to set `data`.
    * Property setter `def data(self, value):` to set `data`.
    * Private instance attribute `next_node`.
    * Property `def next_node(self):` to set `next_node`.
    * Property `def next_node(self, value):` to set `next_node`.
    * Instantiation with `data` and `next_node`:
    `def __init__(self, data, next_node=None):`
  * If a provided `data` attribute is not an integer, a `TypeError`
  exception is raised with the message `data must be an integer`.
  * If a provided `next_node` attribute is not a `Node` or `None`, a
  `TypeError` exception is raised with the message `next_node must be a
  Node object`.
  * The class `SinglyLinkedList` is defined with:
    * Private instance attribute `head`.
    * Instantiation `def __init__(self):`
    * Public instance method `def sorted_insert(self, value):` that inserts a
    new `Node` into the correct sorted position in the list increasing order).

* **8. Print Square instance**
  * [101-square.py](./101-square.py): Python class `Square` that defines a square. Builds on
  [6-square.py](./6-square.py) with:
    * Method `__str__` to set printing of a `Square` instance equivalent to
    `my_print()`.

* **9. Compare 2 squares**
  * [102-square.py](./102-square.py): Python class `Square` that defines a square. Builds on
  [101-square.py](./101-square.py) with:
    * Methods `__eq__`, `__ne__`, `__lt__`, `__le__`, `__gt__`, and `__ge__`,
    to enable usage of `Square` instances with logical operators `==`, `!=`, `<`,
    `<=`, `>`, and `>=`, respectively, based on the square area.

* **10. ByteCode -> Python #5**
  * [103-magic_class.py](./103-magic_class.py): Python function matching exactly a bytecode
  provided by ALX School of Software Engineering.
![Logo](https://i0.wp.com/aceworldpub.com.ng/wp-content/uploads/2022/03/unnamed.png?resize=880%2C528&ssl=1)
