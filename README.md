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

### Variables

#### Primitive data types declaration
```
    int x = 2020;
    float pi = 3.1416f;
    bool continue = true;
```

#### Pointer declaration
```
    int * ptrToInt;
```

#### Pointing to a variable
```
    int * ptrToInt = &x;
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

