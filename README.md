# Brief Reference CPP

**Brief Reference CPP** is a concise reference of the C++ programming languge. 

---

### Comments

#### One line comment
``
// This is a simple comment.
``

#### Multi line comment
```
/*
 * This is a much more elaborated comment that can containt more
 * elaborated information or description about some piece of code.
 */
```

### Preprocessor

#### Include a source file
```
#include <filename>
```

#### Include a source file from the current directory
```
#include "filename"
```

### Macros

#### Macro definition
```
#define PI 3.1416
```

#### Define NULL
```
#define NULL 0
```

### Namespaces

#### Using a namespace
```
using namespace std;
```

### Variables

#### Primitive data types declaration
```
int x = 2020;
float pi = 3.1416f;
bool continue = true;
```

### Pointers

#### Pointer declaration
```
int * ptrToInt;
```

#### Pointing to a variable
```
int * ptrToInt = &x;
```

#### Pointing to nothing
```
int * ptr = NULL;
```

#### Assign a pointer to a pointer
```
int * add = &someVariable;
int * ptr = add;
```

### Functions

#### Declare a function
```
voidd doSomething();
```

#### Define a function
```
void doSomething()
{
}
```

#### Call to a function
```
doSomething();
```

### Methods

#### Call to a static method
```
Utilities::date();
```

### Classes

#### Class definition
```
class Point
{
private:
    int x;
    int y;
public:
    void set_values(int, int);
};
```

#### Instantiate an object of a class
```
Point center;
```
