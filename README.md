# Student Record Management

A menu-driven C project that manages student records using a
singly linked list and file handling.

## Features
- Add, delete, show, modify, load, exit and sort student records
- Roll number is assigned automatically (smallest free number)
- Records are saved in student.dat and loaded at startup

## Files
- student.h : structure and function declarations
- main.c : menu and exit
- stud_add.c, stud_del.c, stud_show.c, stud_mod.c : operations
-stud_load.c : load the data
-stud_exit : exit the program
- stud_save.c : save and load using fprintf and fscanf
- stud_sort.c : sort by name or percentage

## How to compile and run
gcc main.c stud_add.c stud_del.c stud_show.c stud_mod.c stud_load.c stud_exit.c stud_save.c stud_sort.c -o student
./student

## Author
EYEBELL , V26CE2S8
