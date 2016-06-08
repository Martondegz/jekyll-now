---
layout: post
title: principles of OOP
---






The Objects Oriented Programming (OOP) is constructed over four major principles:
**Encapsulation**, **Data Abstraction**, **Polymorphism** and **Inheritance**.<br />

 **1.Encapsulation**:<br />
Encapsulation means that the internal representation of an object is generally hidden from view outside of the object’s definition. Typically, only the object’s own methods can directly inspect or manipulate its fields.<br />

**Encapsulation** is the hiding of data implementation by restricting access to **accessors** and **mutators**.<br />

An **accessor** is a method that is used to ask an object about itself. In OOP, these are usually in the form of properties, which have a get method, which is an accessor method. However, accessor methods are not restricted to properties and can be any public method that gives information about the state of the object.<br />

A **Mutator** is public method that is used to modify the state of an object, while hiding the implementation of exactly how the data gets modified. It’s the set method that lets the caller modify the member data behind the scenes.<br />

Hiding the internals of the object protects its integrity by preventing users from setting the internal data of the component into an invalid or inconsistent state. This type of data protection and implementation protection is called **Encapsulation**.<br />

A benefit of encapsulation is that it can reduce system complexity.

 **2.Abstraction**<br />
**Data abstraction** and encapuslation are closely tied together, because a simple definition of data abstraction is the development of classes, objects, types in terms of their interfaces and functionality, instead of their implementation details. Abstraction denotes a model, a view, or some other focused representation for an actual item.<br />

“An abstraction denotes the essential characteristics of an object that distinguish it from all other kinds of object and thus provide crisply defined conceptual boundaries, relative to the perspective of the viewer.” — G. Booch<br />

In short, data abstraction is nothing more than the implementation of an object that contains the same essential properties and actions we can find in the original object we are representing.<br />

 **3.Inheritance**<br />
**Inheritance** is a way to reuse code of existing objects, or to establish a subtype from an existing object, or both, depending upon programming language support. In classical inheritance where objects are defined by classes, classes can inherit attributes and behavior from pre-existing classes called base classes, superclasses, parent classes or ancestor classes. The resulting classes are known as derived classes, subclasses or child classes. The relationships of classes through inheritance gives rise to a hierarchy.<br />

**Subclasses and Superclasses**<br />
A **subclass** is a modular, derivative class that inherits one or more properties from another class (called the superclass). The properties commonly include class data variables, properties, and methods or functions. The superclass establishes a common interface and foundational functionality, which specialized subclasses can inherit, modify, and supplement. The software inherited by a subclass is considered reused in the subclass.<br />
In some cases, a subclass may customize or redefine a method inherited from the superclass. A superclass method which can be redefined in this way is called a virtual method.<br />

 **4.Polymorphism**<br />
**Polymorphism** means one name, many forms. Polymorphism manifests itself by having multiple methods all with the same name, but slightly different functionality.<br />

There are 2 basic types of polymorphism.<br />
**Overridding**, also called run-time polymorphism. For method overloading, the compiler determines which method will be executed, and this decision is made when the code gets compiled.<br />
**Overloading**, which is referred to as compile-time polymorphism. Method will be used for method overriding is determined at runtime based on the dynamic type of an object.<br />

Reference from:<br />
(http://codebetter.com/raymondlewallen/2005/07/19/4-major-principles-of-object-oriented-programming/
http://en.wikipedia.org/wiki/Object-oriented_programming)

