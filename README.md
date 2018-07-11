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

![](Tutorial-1.png)
 
### Execution result may vary according to the system configuration.
The screenshots of the execution results attached holds system configuration as :
* Processor : Intel Core i5
* RAM : 8 GB
* System Type : 64 bit Operating System

### Time Complexity on Linux ( Ubuntu ) 

* Sorting 100000 Random Numbers Using Quick Sort

![](Time-Complexity-On-Linux.png)

### Time Complexity on Windows

* Sorting 100000 Random Numbers Using Quick Sort

![](Time-Complexity-On-Windows.JPG)

### Time Complexity on RStudio

* Sorting 50000 Random Numbers Using Quick Sort 

![](Time-Complexity-On-RStudio.JPG)
