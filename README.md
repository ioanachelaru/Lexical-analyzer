# Lexical analyzer

## Problem statement

The scanner's input will be a text file containing the source program, and will produce as output the following:

- PIF - Program Internal Form

- ST  - Symbol Table

In addition, the program should be able to determine the lexical errors, specifying the location, and, if possible, the type of the error.

## User guide

The scanner uses the following commands:

```
lex lex-analizer.l
gcc lex.yy.c
./a.out greatest-common-divisor.txt
```

The first command generates the lex.yy.c file, while the second one generates the executable a.out.
