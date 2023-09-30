# HowtoCPP
C++ quick tutorial
## Introduction
Since I'm busy learning C++, why not writing it here? 

## CLI programs

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

the others functions are placed before the main function or after (in which case you will have to forward the declaration by typing the function name before the main, but with a semicolon instead of curly braces).

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


## GUI programs

