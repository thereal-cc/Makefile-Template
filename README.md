# Makefile for my C projects  

As I've been developing more C projects, I've found that I use the same makefile almost every time for each project.  
This is that makefile.  
This also serves as a template for future projects, so feel free to make changes to make this better.  
P.S. ``` make clean ``` only works right now on macOS/Linux, but I'm working on a Windows version that doesn't use ``` -rf ```.

## Usage

This makefile involves the use of 3 different folders:  

* `src` - This is where all of your source files go (Header files are included in a nested `include` folder).
* `obj` - This is where all of your object files go.
* `bin` - This is where your executable goes.  
