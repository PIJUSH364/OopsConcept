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
  <li><h3>Public :<h3/> </li>members can be accessed outside the class
  <li><h3>private:<h3/></li>members cannot be accessed outside the class.
  <li><h3>Protected:<h3/></li>members cannot be accessed(viewed) from outside the class, but can be accessed in inherited classes(subclasses).
 </ul>

<h2>Declaring Objects in C++ <h/3>

##### When a class is defined only the blueprint of data structure is defined as no memory is allocated. To use data and its member function we can declare objects. We can declare objects by mentioning the class followed by the user-defined object name.

### Syntax :

```c++
 Class ObjectName;
```

### Example :

```c++
 Dog dog;
```

<h3>Significance of Class and Object in C++</h3>

##### The concept of class and object in C++ allows real-life analogies to be included in the programming. Using classes, data is given the highest importance. The following are some of the significant points to keep in mind.

<ul>
 <li><h3>Data hiding:<h3/> </li> Using access specifiers, a class stops data from being accessed from the outside world. Classes have the ability to set permissions to limit who has access to the data.

 <li><h3>Code Reusability:<h3/> </li> With the aid of inheritance, you may reduce code redundancy by employing reusable code. Similar functionality and features can be inherited by other classes, making the code cleaner

  <li><h3>Data binding: <h3/> </li>The data elements and their associated operations are bonded together under one umbrella, increasing the data's security
   <li><h3>Flexibility:<h3/> </li>  The principle of polymorphism allows you to use a class in a variety of ways. This increases the flexibility of a program.
</ul>

<h3>Array of Objects </h3>

#### An array in C++ is a collection of data stored in contagious memory locations in the memory. An array can be of int, string, or char as well as of some derived data types like structures, pointers, etc. An array of objects is a collection of objects of some class type.

### Syntax :

```c++
 ClassName ObjectName[number of objects];

```

### Example :

```c++
Dog dog[5];    //array of 5 objects of class Dog

```

<p align="left"> <img src="https://scaler.com/topics/images/array-of-objects.webp" alt="pijush364" /> </p>

