# Exercise 2 - Using Makefiles to Build

This exercise shows how to create a _makefile_ file and provides the basic steps the tools takes when using `make fileName`

## Notes:

- `make ex1`
1. Does the file _ex1_ exist already?
2. No. Okay, is there another file that starts with _ex1_?
3. Yes, it's called _ex1.c_. Do I know how to build _.c_ files?
4. Yes, I run this command `cc ex1.c -o ex1` to build them.
5. I shall make you one _ex1_ by using _cc_ to build it from _ex1.c_.

- `CFLAGS="-Wall" make ex1` > tells the compiler _cc_ to report all warnings

