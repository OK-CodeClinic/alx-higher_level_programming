# Python - Inheritance

### **General Knowledge**
**In this project, i started learning;**
1. Why Python programming is awesome
2. How to open a file
3. How to write text in a file
4. How to read the full content of a file
5. How to read a file line by line
6. How to move the cursor in a file
7. How to make sure a file is closed after using it
8. What is and how to use the with statement
9. What is JSON
10. What is serialization
11. What is deserialization
12.How to convert a Python data structure to a JSON string
13. How to convert a JSON string to a Python data structure

## Author

- [Kehinde Omokungbe](https://www.github.com/OK-CodeClinic)
## Rewuirements
### Python requirements
- Allowed editors: vi, vim, emacs
- All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)
- All your files should end with a new line
- The first line of all your files should be exactly #!/usr/bin/python3
- A README.md file, at the root of the folder of the project, is mandatory
- Your code should use the pycodestyle (version 2.8.*)
- All your files must be executable
- The length of your files will be tested using wc

### Python Test Cases
- Allowed editors: ```vi```, ```vim```, ```emacs```
- All your files should end with a new line
- All your test files should be inside a folder ```tests```
- All your test files should be text files (extension: ```.txt)```
- All your tests should be executed by using this command: ```python3 -m doctest ./tests/*```
- All your modules should have a documentation ```(python3 -c 'print(__import__("my_module").__doc__)')```
- All your classes should have a documentation ```(python3 -c 'print(__import__("my_module").MyClass.__doc__)')```
- All your functions (inside and outside a class) should have a documentation ```(python3 -c 'print(__import__("my_module").my_function.__doc__)'``` and ```python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)')```
- A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of it will be verified)
- We strongly encourage you to work together on test cases, so that you don’t miss any edge case


### Documentation
- Do not use the words import or from inside your comments, the checker will think you try to import some modules
## Tasks

#### **Mandatory Tasks** 
* **0. Read file**
  * [0-read_file.py](./0-read_file.py): Python function that prints the contents of a UTF8 text
  file to standard output.

* **1. Number of lines**
  * [1-number_of_lines.py](./1-number_of_lines.py): Python function that returns the number of lines
  contained in a text file.

* **2. Read n lines**
  * [2-read_lines.py](./2-read_lines.py): Python function that prints `n` lines of a UTF8 text
  file to standard output.

* **3. Write to a file**
  * [3-write_file.py](./3-write_file.py): Python function that writes a string to a UTF8 text
  file and returns the number of characters written.

* **4. Append to a file**
  * [4-append_write.py](./4-append_write.py): Python function that appends a string to the end of a
  UTF8 text file and returns the number of characters appended.

* **5. To JSON string**
  * [5-to_json_string.py](./5-to_json_string.py): Python function that returns the JSON string
  representation of an object.

* **6. From JSON string to Object**
  * [6-from_json_string.py](./6-from_json_string.py): Python function that returns the Python object
  represented by a JSON string.

* **7. Save Object to a file**
  * [7-save_to_json_file.py](./7-save_to_json_file.py): Python function that writes an object to a text
  file using JSON representation.

* **8. Create object from a JSON file**
  * [8-load_from_json_file.py](./8-load_from_json_file.py): Python function that creates an object from a
  `.json` file.

* **9. Load, add, save**
  * [9-add_item.py](./9-add_item.py): Python script that stores all command line arguments to a
  Python list saved in the file `add_item.json`.

* **10. Class to JSON**
  * [10-class_to_json.py](./10-class_to_json.py): Python function that returns the dictionary
  description for simple Python data structures (lists, dictionaries, strings,
  integers and booleans).

* **11. Student to JSON**
  * [11-student.py](./11-student.py): Python class `Student` that defines a student. Includes:
    * Public instance attributes `first_name`, `last_name`, and `age`.
    * Instantiation with `first_name`, `last_name`, and `age`:
    `def __init__(self, first_name, last_name, age):`.
    * Public method `def to_json(self):` that returns the dictionary
    representation of a `Student` instance.

* **12. Student to JSON with filter**
  * [12-student.py](./12-student.py): Python class `Student` that defines a student. Builds on
  [11-student.py](./11-student.py) with:
    * Public method `def to_json(self, attrs=None):` that returns the
    dictionary representation of a `Student` instance.
    * If `attrs` is a list of strings, only the attributes listed are
    represented in the dictionary.

* **13. Student to disk and reload**
  * [13-student.py](./13-student.py): Python class `Student` that defines a student. Builds on
  [12-student.py](./12-student.py) with:
    * Public method `def reload_from_json(self, json):` that replaces all
    attributes of the `Student` instance using the key/value pairs listed in `json`.
    * The method assumes `json` is a dictionary containing attributes with
    name/value corresponding to key/value.

* **14. Pascal's Triangle**
  * [14-pascal_triangle.py](./14-pascal_triangle.py): Python function that returns a list of lists of
  integers representing Pascal's triangle of size `n`.
  * Assumes the size parameter `n` is an integer.
  * If `n` is less than or equal to `0`, returns an empty list.

* **15. Search and update**
  * [100-append_after.py](./100-append_after.py): Python function that inserts a line of text to a
  file after each line containing a specified string.

* **16. Log parsing**
  * [101-stats.py](./101-stats.py): Python script that reads lines from standard input. After
  every 10 lines or the input of a keyboard interruption (`CTRL + C`), computes the
  following metrics:
    * Total file size up that point: `File size: <total size>`
    * Status code of each read line, printed in ascending order:
    `<status code>: <number>`
  * Input format: `<IP Address> - [<date>] "GET /projects/260 HTTP/1.1"
  <status code> <file size>`

* **17. Hack the VM**
  * [read_write_heap.py](./read_write_heap.py): Python script that finds and replaces a string in the heap of a running process.
  * Usage: `read_write_heap.py pid search_string replace_string` where `pid` is the process ID of the running process and strings are represented in ASCII.
  * Only looks in the heap of the process.
  * On a usage error, prints an error message to `stdout` and exits with the status code `1`.
![Logo](https://i0.wp.com/aceworldpub.com.ng/wp-content/uploads/2022/03/unnamed.png?resize=880%2C528&ssl=1)
