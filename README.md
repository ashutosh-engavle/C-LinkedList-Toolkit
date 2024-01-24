
# Singly Linked List Operations in C

## Overview
This C program is a comprehensive implementation of various operations on singly linked lists. It allows the creation and manipulation of multiple linked lists, supporting a wide range of operations including insertion, deletion, sorting, searching, and more.

## Features
- **Dynamic Creation of Multiple Linked Lists:** Create up to 100 singly linked lists dynamically.
- **Insertion Operations:** Insert nodes at the beginning, end, after a given node, or insert sorted nodes.
- **Deletion Operations:** Delete nodes from the beginning, end, after a given node, or delete a node with a specific value.
- **Sorting:** Sort lists in ascending or descending order.
- **Searching:** Search for an element across all lists.
- **List Manipulation:** Operations like copying, concatenating, reversing, and splitting lists.
- **Utility Functions:** Functions for node creation, list creation, and more.

## Usage
Run the program and follow the on-screen prompts to perform various operations on the linked lists. 
- Enter the number of linked lists to work with.
- Choose from a menu of operations.
- Provide necessary input for chosen operations (e.g., values for insertion, lists for copying).

## Compilation
Compile the program with a C compiler (e.g., GCC) using the following command:
```
gcc -o linked_list linked_list.c
```
Then, run the executable:
```
./linked_list
```

## Program Structure
The program consists of the following main components:
- **Structures:** Definition of the `node` structure.
- **Utility Functions:** `getNode`, `getStart`, etc., for node and list creation.
- **List Operations:** Functions for each operation (insertion, deletion, etc.).
- **Main Function:** Interface for interacting with the user and executing operations.

## Limitations
- The program is limited to a maximum of 100 linked lists.
- Error handling is minimal, so careful input validation is necessary.
- The program operates in a console environment.

## Author
[Your Name or Identifier]

