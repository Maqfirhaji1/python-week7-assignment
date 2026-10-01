PLP Python Week 7 — Shopping List Manager

This repository contains my Week 7 Python assignment, Shopping List Manager.

Project Files

list_warmup.py — Demonstrates basic list creation, index access, .append(), .remove(), and len().

shopping_list.py — Provides an interactive shopping list manager using a menu, loops, .append(), .remove(), and membership checking with in.

list_report.py — Generates a report by numbering items, counting item names with more than four letters, and finding the longest item using a loop.

screenshots/ — Contains screenshots showing the programs running successfully.

Why check before calling .remove()?

Checking whether an item is in the list before calling .remove() is safer because .remove() raises a ValueError if the item does not exist. Using if item in shopping_list prevents that error and allows the program to continue running normally.

Skills Practiced

This assignment demonstrates:

Creating and accessing lists

List indexing

.append()

.remove()

in membership checking

len()

for loops

if statements

Interactive input

Building a simple menu-driven program

Comparing values in a loop

Repository Structure
plp-python-week7/
│
├── list_warmup.py
├── shopping_list.py
├── list_report.py
├── README.md
│
└── screenshots/
    ├── list_warmup.png
    ├── shopping_list.png
    └── list_report.png

Running the Programs

Run the warmup:

python list_warmup.py


Run the shopping list manager:

python shopping_list.py


Run the report:

python list_report.py

Expected Results
List Warmup

The program demonstrates adding and removing fruits and reports the number remaining.

Shopping List Manager

The program allows the user to add, remove, display, and finish managing shopping items without crashing when a missing item is requested for removal.

List Report

The program prints:

1. bread
2. avocado
3. milk
4. sweet potatoes
5. tea
Items with more than 4 letters: 3
Longest item: sweet potatoes

Author

PLP Python Programming — Week 7 Assignment