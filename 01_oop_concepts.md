# Object Oriented Programming Concepts
This article presents a brief summary of object-oriented programming.

## Table of Content
- What is OOP?
- What is an Object?
- What is a Class?
- Benefits of use OOP

### What is OOP?
The OOP is the acronymous of **O**bject **O**riented **P**rogramming, a computer programming philosophy that consists of breaking down real-world problems into individual parts called objects. Each object can have certain properties and perform certain actions, that is defined by the nature or type of object.

Since the advent of object-oriented programming, many programming languages have emerged to work with this philosophy: Smalltalk (the first one), C, C++, Java, C#. Regarding this topic, there are a large number of trends, variants or opinions regarding the fidelity that each language has with the foundations of the OOP. There are 100% OOP languages like Smalltalk in which everything is object, the primitive values and even classes are objects. There are languages that adopt all the fundamentals of OOP but are not completely OOP like C++, Java, C#. JavaScript is not an OOP programming language, instead is a prototype-based and dynamic-typing language which can emulate certain aspects of the OOP like inheritance and encapsulation.

### What is an Object?
For example, if we wanted to model a dog in the world of OOP, we could say that a dog has the following properties: nickname, breed, hair color, height, weight and age; and that he can perform the following actions: bark, jump, run, sleep and eat. So in OOP, my pet Nicky is an **Object** with brown hair, 10kg weight, 25cm tall, 2-year-old.

### What is a Class?
In OOP an Object are defined by a **Class**. A class is an extensible program-code-template for creating objects, providing fields to hold the attributes (data) and implementating actions (methods). In many languages, the class have a procedure called constructor which is intended to create an **instance** of the class, which results in the creation of the object. In the previous example, my dog Nicky would be an instance of the Dog class.

### Benefits of use
The principle of the OOP is to decompose a real world problem into smaller parts, that have very well defined characteristics and behaviors, which can be used to compose the solution to the problem. in this model each part is an object that has a specific purpose. This provides the following benefits:
1. Modularity for easier troubleshooting
The objects are self-contained and each piece of functionality does its thing. This mode allows an IT team to work on multiple objects simultaneously and minimizes the possibility that one person can duplicate the functionality of another.
2. Reuse of code through inheritance
This is the ability of a new class to be created, from an existing class by extending it. In my example I can create the Animal class and from this class create a variety of objects that inherit the characteristics of Animal, I can even extend the characteristics of a particular animal,
For this, the Animal class should have a more generic interface, which allows a great variety of animal types to be inherited, such as eagle, snake, whale and dog. the animal interface would be like: properties: phylum, class, order, family, genus, species, color, weight, size, canRun, canJump, canSwim, canFly; methods such as: move, feed, rest
