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

#### Delete and object
```
delete object;
```

#### Assign a pointer to a pointer
```
int * add = &someVariable;
int * ptr = add;
```

#### Pointer to an object
```
Book book;
Book * somebook = &book;
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

#### Instantiate an object of a class
```
Point center;
```

#### Instantiate an object of a class with specific values
```
Point center(0, 0);
```

#### Create a new object of a class in the heap
```
new Point();
```
