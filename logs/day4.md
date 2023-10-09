# Day 4: Adding dynamic tape to my brainfuck interpreter

[Link to the code](https://github.com/lsferreira42/bli)

Today i worked on enabling a dynamic tape in my brainfuck interpreter, it's handled by an auxiliar function that grows the array when needed.
This introduced some bugs in the interpreter, still looking into it.

To help me debug these bug's, i also wrote a debug function and a step by step mode that you can control by command line flags


# Conclusion

Memmory allocations in C require harder study, also dealing with boundaries in arrays sucks

[Back to Log](../README.md#log)