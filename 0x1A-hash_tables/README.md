# C - Hash tables

### **General Knowledge**
**In this project, i started learning;**
1. What is a hash function
2. What makes a good hash function
3. What is a hash table, how do they work and how to use them
4. What is a collision and what are the main ways of dealing with collisions in the context of a hash table
5. What are the advantages and drawbacks of using hash tables
6. What are the most common use cases of hash tables

## Author

- [Kehinde Omokungbe](https://www.github.com/OK-CodeClinic)
## General Requirements
- Allowed editors: vi, vim, emacs
- All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
- All your files should end with a new line
- A README.md file, at the root of the folder of the project is mandatory
- Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
- You are not allowed to use global variables
- No more than 5 functions per file
- You are allowed to use the C standard library
- The prototypes of all your functions should be included in your header file called hash_tables.h
- Don’t forget to push your header file
- All your header files should be include guarded
## Tasks

#### **Mandatory Tasks*** 
**0. >>> ht = {}**
  * [0-hash_table_create.c](./0-hash_table_create.c): C function that creates a `hash_table_t`
  hash table.
    * If the function fails - returns `NULL`.
    * Otherwise - returns a pointer to the new hash table.

* **1. djb2**
  * [1-djb2.c](./1-djb2.c): C function that implements the djb2 hashing algorithm.

* **2. key -> index**
  * [2-key_index.c](./2-key_index.c): C function that returns the index at which a key/value
  pair should be stored in the array of a `hash_table_t` hash table.

* **3. >>> ht['betty'] = 'holberton'**
  * [3-hash_table_set.c](./3-hash_table_set.c): C function that adds an element to a
  `hash_table_t` table.
    * The parameter `key` cannot be an empty string.
    * Returns `1` on success, `0` otherwise.

* **4. >>> ht['betty']**
  * [4-hash_table_get.c](./4-hash_table_get.c): C function that retrieves a value associated
  with a key in a `hash_table_t` hash table.
    * If `key` cannot be matched - returns `NULL`.
    * Otherwise - returns the value associated with `key`.

* **5. >>> print(ht)**
  * [5-hash_table_print.c](./5-hash_table_print.c): C function that prints a `hash_table_t`
  hash table.
    * Prints each `key`/`value` pair in the order they appear in the array of the hash table.
    * Does not print anything if the hash table is `NULL`.

* **6. >>> del ht**
  * [6-hash_table_delete.c](./6-hasb_table_delete.c): C function that deletes a
  `hash_table_t` hash table.

### **Advanced Tasks**

* **7. $ht['Betty'] = 'BestSchool'**
  * [100-sorted_hash_table.c](./100-sorted_hash_table.c): C functions that define a sorted
  hash table `shash_table_t`.
    * Identical in function to a `hash_table_t` hash table except key/value
    pairs are inserted in alphabetical order according to the ASCII value of the key.
    * Key/value pairs are printed in the order they are sorted.
    * Includes a function `shash_table_print_rev()` that prints the hash table
    in reverse order.
![Logo](https://i0.wp.com/aceworldpub.com.ng/wp-content/uploads/2022/03/unnamed.png?resize=880%2C528&ssl=1)
