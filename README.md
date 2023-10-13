# What is a Program?

## Learning Goals

- Describe a program.
- Distinguish between interpreted and compiled programs.
- List and describe the words that compose code: keywords, barewords, and data.
- Identify when and why errors occur in programming.

## What's a Program?

All programs are files on your computer filled with text. That text has a
special syntax we call code. The programming language you're using defines the
syntax of the code you are allowed to write. Programs are converted to
[machine code](https://en.wikipedia.org/wiki/Machine_code) so that the computer
can understand it.

## Interpreted vs Compiled

Depending on the programming language you're using, it will either be a
[compiled language](http://en.wikipedia.org/wiki/Compiled_language) or an
[interpreted language](http://en.wikipedia.org/wiki/Interpreted_language).
Compiled programs will first be converted to machine code and then you will be
able to run the program. Interpreted languages will be interpreted and converted
to machine code at run time.

## Words in a Program

Every word and character in a program has to be valid code for the Python
language. Basically, every word can be one of three possible things:

1. A Python keyword, something that's part of the Python language.
2. Literal data, things like "Strings" and numbers like 1 or 2.
3. Barewords you define and create, things like variables and methods.

Anything that isn't one of those is invalid and the Python interpreter will
throw an error.

Let's say you ran a program, and saw the following output (pay attention to the
last line):

```python
Programs are composed of basically three things:
A language's keywords, like 'if' or 'for' (35 in Python).
Literal pieces of data like this very sentence (string).
Finally, barewords, or variables, that are set equal to things.
Anything that isn't one of those will cause an error.
NameError: name 'hello' is not defined.
```

That last line, `NameError: name 'hello' is not defined.` is telling you that
there was an error caused by an unrecognized word in the source of our program.

## Conclusion

Now that we have reviewed what a program is we will run our first Python program
in the next lesson!
