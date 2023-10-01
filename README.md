# HowtoCPP
C++ quick tutorial
## Introduction
Since I'm busy learning C++, why not writing it here? 

## CLI basic softwares

### Basics

Any code will require a main function to work :
```
int main()
{

}
```

Included packages are written like this and have to be outside the main function :

```
#include <nameofyourpackage>
```

The others functions are placed before the main function or after (in which case you will have to forward the declaration by typing the function name before the main, but with a semicolon instead of curly braces).

```
int functionplacedbefore();
int functionplacedafter();

int main()
{

}

int functionplacedafter()
{

}
```
Every instruction you type, should have a semicolon at the end of it ```;```

### Variables

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
### Inputs and outputs
### Conditions
### Loops

### Pointers 

A pointer is a variable that holds the memory address of another variable. A pointer needs to be dereferenced with the * operator to access the memory location it points to

Declare your pointer like this :

```
int i = 3; 
int *ptr = &i; 
```

### References

A reference variable is an alias, that is, another name for an already existing variable. A reference, like a pointer, is also implemented by storing the address of an object. 
A reference can be thought of as a constant pointer (not to be confused with a pointer to a constant value!) with automatic indirection, i.e., the compiler will apply the * operator for you.

### Static Variables And Pass By Reference

You can pass an argument to a function by VALUE or by REFERENCE.
If you pass by value, a temporary copy of this value is created for the function ONLY.

## CLI advanced softwares

## GUI softwares

