<h1 align="center">Oops In C++</h1>

## Overview

#### C++ is an object-oriented programming language that is used to implement real-world entities like inheritance, hiding, polymorphism, etc into programs. Object-oriented programming languages achieve this using classes and object

## What is a Class in C++?

#### A class in C++ is a user-defined type or data structure declared with a keyword class that has data and functions as its members. A class can be used by declaring an instance of that class which is nothing but an object in C++

## Ex.
#### In real life, we see dogs with different breeds or classes but there are some common characteristics such as they have a tail, they bark, they sniff, etc. So, instead of creating a different class for every dog, we can define a single class with common properties of dogs. Hence, Classes act as a user-defined data type to create objects with similar properties.

## What is an Object in C++?

#### A class is merely a blueprint of data. An object is a data structure that is an instance of a class. So when a class is created no memory is allocated but when an instance is created by declaring an object, memory is then allocated to store data and perform required functions on them



<p align="left"> <img src="https://scaler.com/topics/images/object-in-cpp.webp" alt="pijush364" /> </p>


## Class Example

```c++
class ClassName
{
    Access specifier: 
    Data members;
    Member Functions()
    {
        // member function defintion
    }
};


```

### Let's take an example of a Dog class having data members breed and color followed by member functions

```c++
class Dog{                         // class ClassName
    public:                        //Access specifiers
        string breed, color;       //Data members

        void displayColor(){       //Member functions
            cout<<color<<" ";
        }

        void displayBreed(){
            cout<<breed<<" ";
        }
};                                // end with semicolon

```

### Note:
##### Access specifier defines how the members of the class can be accessed. In C++, there are 3 types of access specifiers: public, private, and protected.

<ul>
  <li><h3>Public :<h3/>members can be accessed outside the class</li>
  <li><h3>private:<h3/>members cannot be accessed outside the class.</li>
  <li><h3>Protected:<h3/>members cannot be accessed(viewed) from outside the class, but can be accessed in inherited classes(subclasses).</li>
 </ul>
