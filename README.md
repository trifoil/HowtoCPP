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
    4. [Print outputs](#cout)
    5. [Chars and strings](#charandstrings)
    6. [Standard input](std#)
    7. [If statement](if#)
    8. [If-else](#ifelse)
    9. [Loops](#loops)
    10. [RNG (random number generator)](#rng)
    11. [Bools](#bools)
    12. [Functions](#functions)
    13. [Parameters and forward declarations](#)
    14. [Static vars and pass by reference](#)
    15. [Arrays](#)
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

To write comments in your code there are two ways :

Either line comments :

```
// this is a line comment
```

Or block comments, that can include multiple lines ```/*``` starts the comment, and ```*/``` ends it :

```
/*  comment
    also comment
*/
```

---


### The basic program <a name="base"></a>

Any code will require a main function to work (your working code has to be in the brackets :
```
int main(){

}
```

Arguments are placed in the ```()``` and the main code is placed in the ```{}```

The int return type indicates the program's exit status (0 usually means successful execution, while non-zero values indicate errors). 

Included libraries are written like this and have to be outside the main function :

```
#include <nameofyourpackage>
```

This allows the use functionalities from external libraries, and without them, the compiler won't recognize certain functions or objects.

---

### Variables <a name="vars"></a>

In C++, variables are essential components that store and manage data in your program. Understanding how to declare and use variables is fundamental to writing effective code.

#### Integer Variables:

Integers represent whole numbers and can be positive or negative. The `int` data type is commonly used for integers. Here's how you declare an integer variable:

```cpp
int variableName = <value>;
```

For example:

```cpp
int age = 25;
```

Keep in mind that the size of an `int` may vary depending on the compiler and platform. If you need to represent only non-negative integers, you can use `unsigned int`.

#### Floating-Point Variables:

Floating-point numbers are used to represent values with a fractional part. There are two main types in C++: `float` and `double`. 

- **Float:**
  ```cpp
  float variableName = <value>f;
  ```
  For example:
  ```cpp
  float temperature = 23.5f;
  ```

  Remember to include the `f` at the end to explicitly specify that the number is a `float`.

- **Double:**
  ```cpp
  double variableName = <value>;
  ```
  For example:
  ```cpp
  double pi = 3.14159;
  ```

  Use `double` when you need higher precision, as it can represent a broader range of values compared to `float`.

#### Character Variables:

Characters are used to store individual characters. The `char` data type is employed for this purpose:

```cpp
char variableName = '<character>';
```

For example:

```cpp
char grade = 'A';
```

#### Naming Conventions:

- Variable names must start with a letter or an underscore.
- Subsequent characters can be letters, numbers, or underscores.
- Avoid using reserved keywords.
- Choose descriptive names to enhance code readability.

Understanding these basics about variables sets the stage for more complex programming tasks. In the next chapter, we'll explore how to manipulate variables through operations and expressions.

---







## OOP (CLI) <a name="oop"></a>

## Advanced programming (Graphics) <a name="advanced"></a>

## Conclusion <a name="conclusion"></a>

## Sources <a name="sources"></a>