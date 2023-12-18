[![en](https://img.shields.io/badge/lang-en-gre.svg)](https://github.com/trifoil/HowtoCPP/blob/main/README.md) 
# HowtoCPP
Complete basics in C++ programming. (Why TF am I even doing that? At least, it's not assembly)
## Table of contents <a name="toc"></a>
0. [Table of contents](#toc)
1. [Introduction](#intro)
2. [Compiler](#compiler)
    <details>
    <summary>More</summary>

    1. [Install the compiler](#compilerinstall)
    2. [Rubn the compiler](#compileruse)
    </details>
3. [The basics (CLI)](#basics)
    <details>
    <summary>More</summary>

    1. [Comments](#comments)
    2. [The basic program](#base)
    3. [Variables](#vars)
    4. [Chars and strings](#charandstrings)
    5. [Standard input](std#)
    6. [If statement](if#)
    7. [If-else](#ifelse)
    8. [Loops](#loops)
    9. [RNG (random number generator)](#rng)
    10. [Bools](#bools)
    11. [Functions](#functions)
    12. [Parameters and forward declarations](#)
    13. [Static vars and pass by reference](#)
    14. [Arrays](#)
    </details>

4. [OOP (CLI)](#oop)
    <details>
    <summary>More</summary>

    1. [Classes](#classes)
    2. [Objects](#objects)
    2. [Access specifiers](#)
    2. [Files and constructor separation](#)
    2. [Vectors](#)
    2. [Lists](#)
    2. [File IO / advanced input](#)
    2. [Printf](#)
    2. [](#)
    2. [](#)
    </details>

5. [Advanced programming (Graphics)](#advanced)
    <details>
    <summary>More</summary>

    1. [](#)
    2. [](#)
    </details>


6. [Conclusion](#conclusion)
7. [Sources](#sources)

## Introduction <a name="intro"></a>

This tutorial goes through procedural and object oriented programming.

The last part is dedicated to the use of the SDL2 library.

My tutorial is aimed at Linux users. For further explanations about installing libraries or software on windows, do your own research.

## Compiler <a name="compiler"></a>

### Compiler installation <a name="compilerinstall"></a>

### Compiler use <a name="compileruse"></a>

## The basics (CLI) <a name="basics"></a>

### Comments <a name="comments"></a>

### The basic program <a name="base"></a>

Any code will require a main function to work (your working code has to be in the brackets :
```
int main(){}
```

Arguments are placed in the ```()``` and the main code is placed in the ```{}```

Included packages are written like this and have to be outside the main function :

```
#include <nameofyourpackage>
```

### Variables <a name="vars"></a>

Integers (which value can go from -2147483648 to 2147483647) are declared as :

```
int variableName = value;
```

Doubles can represent any numerical value in the compiler, including decimal values :

```
double variableName = value;
```

Floats. You can use an f placed right after the variable value to mention explicitly that the number is float. Otherwise the compiler will see it as double and which will never match to a float parameter given in the function :

```
float variableName = valuef;
```

## OOP (CLI) <a name="oop"></a>

## Advanced programming (Graphics) <a name="advanced"></a>

## Conclusion <a name="conclusion"></a>

## Sources <a name="sources"></a>