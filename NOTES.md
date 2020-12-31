# Build Your Own Lisp

## Chapter 2: Build Environment & Installation

* Find the version of `C`: `cc --version`
* file: `hello.c`
	* First line is a *header*, which allows functions from `stdio.h` to be 
		used. One of such functions is `puts` (line 4)
	* Every `C` file needs a function to be declared called `main`, which 
		outputs an `int`, and takes in the standard arguments.
		* All programs start running from this function
	* `puts` is short for "put string"
* Compilation in c
	* `cc -std=c99 -Wall hello.c -o hello`
		* `std` is the version of `C` used.
* Debugging C
	* [gdb](https://web.archive.org/web/20140910051410/http://www.dirac.org/linux/gdb/) can be used to debug `C` programs.
		* On Mac, it's usually `lldb`.
		* On Linux or Mac there is also 
			[Valgrind](https://www.cprogramming.com/debugging/valgrind.html)
	* There is also the online [C reference](https://en.cppreference.com/w/c)
