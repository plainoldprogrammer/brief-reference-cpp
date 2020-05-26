# Brief Reference CPP

**Brief Reference CPP** is a concise reference of the C++ programming languge. 

---

### Comments

#### One line comment
```
// This is a simple comment.
```

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

### Operators

#### Logical Operators
```
!    // Not
&&   // And
||   // Or
```

### Variables

#### Primitive data types declaration
```
int x = 2020;
float pi = 3.1416f;
double pi = 3.414159;
char letter = 'a';
bool continue = true;
```

### Extern Variables

#### Define in an implementation file:

```
extern const float pi = 3.1416;
```

#### Declare it when you want to use:

```
extern const float pi;
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

#### Delete and object
```
delete object;
```

#### Assign a pointer to a pointer
```
int * add = &someVariable;
int * ptr = add;
```

#### Declare a pointer to pointer to pointer
```
int ***ptr;
```

#### Pointer to an object
```
Book book;
Book * somebook = &book;
```

### Functions

#### Declare a function
```
void doSomething();
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

### Class member functions

#### Declare a member function
```
class Rectangle
{
public:
    int calculate_area(int, int);
};
```

#### Define a member function
```
int Rectangle::calculate_area(int height, int width)
{
    return height * width;
}
```

#### Call to a member function
```
Rectangle terrain;
cout << terrain.calculate_area();
```

### Class static member functions

#### Declare a static member function
```
class Person
{
public:
    static int get_max_id();
};
```

#### Define a static member function
```
int Person::get_max_id()
{
    return id;
}
```

#### Call to a static member function
```
Utilities::date();
```

### Classes

#### Class definition
```
class Point
{
protected:
private:
    int x;
    int y;
public:
    void set_values(int, int);
};
```

#### Class inheritance
```
class Pixel : Point
{
};
```

#### Instantiate an object of a class
```
Point center;
```

#### Instantiate an object of a class with specific values
```
Point center(0, 0);
```

#### Create a new object of a class in the stack
```
Point center;
```

#### Create a new object of a class in the heap
```
new Point();
```

#### Delete an object created with new
```
Point *ptrPoint = new Point();
delete ptrPoint;
```

### Headers

#### Header Guards
```
#ifndef UNIQUE_CLASS_NAME
#define UNIQUE_CLASS_NAME
// declarations
#endif
```
