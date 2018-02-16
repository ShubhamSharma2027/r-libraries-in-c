# r-libraries-in-c
R is a language and environment for statistical computing and graphics. It includes an effective data handling and storage facility, a large, coherent, integrated collection of intermediate tools
for data analysis. We aim to develop R libraries to deliver good performance, it will support
basic form operations and understanding the space time complexity in different platforms.

## The objective is to :-
1) Develop  R libraries in C
2) Visualization of data points
3) Comparative study of space time complexity on different platforms

## How to Build .so file from .c file using gcc on Linux ( Ubuntu ) Terminal

`gcc -shared -o sortingLibrary.so -fPIC sortingLibrary.c`

## Steps to load the .so file on R Console using Terminal : 

` dyn.load('sortingLibrary.so') ` 

 ` .C("main") ` 

This will execute the library file.
In case of any issue email me at : isharmashubham@outlook.com

