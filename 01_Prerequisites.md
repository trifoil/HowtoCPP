# Prerequisites

## The code editor

I use Codium which is a fork of VSCode. It is compiled for a lot of OS and is free of bloat/spyware.

## The compiler

I use g++ as a compiler.

The lost basic usage for the g++ compiler is :

```
g++ main.cpp -o main
```

It will output an executable named "main" from your source file "main.cpp"

To include a library when compiling, use the -w argument :

```
g++ main.cpp -w -lSDL2 -lSDL2_ttf -o main
```

