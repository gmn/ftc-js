# ftc-js: Fast two-argument calculator.

ftc-js: Fast two-argument calculator, re-written for node.js for commandline

## Features

This is a much improved version of an old commandline tool that I have been
using for nearly a decade. It was written originally in C and never was even
close to being good code.  In fact the version that exists up to this day has
several buffer overruns that I never bothered to fix due to mis-uses of strnlen()

ftc-js however supports: 
* Proper order of arguments: ```ftc 1 + 2 * 3``` ==> equals 7, not 9

* Indiscriminate command-line argument formatting: can do ```ftc "10 + 9"``` or ```ftc 10 + 9``` interchangably, with the only exception that the '*' asterix operator must be included in quotes or the shell will expand it to match directory contents, a side-effect of bash-like interpreters.

* Better number base conversion. Print answers in: **-H** Hexadecimal, **-O** Octal, **-B** Binary

* Is no longer *Two Argument* ;)

## Contact

Mail: **greg AT naughton.org** with questions/comments
