# Clean Code
 
 In this Document we will learn how to write code in better approach.

 
 ## Naming And Conventions

Names are everywhere in software. We name our variables, our functions, our arguments, classes, and packages. We name our source files and the directories that contain them. We name our jar files and war files and ear files. We name and name and name. Because we do so much of it, we’d better do it well. What follows are some simple rules for creating good names.


### CONVENTIONS
Every programming languages has some **conventions** that help programmers to write code in more comprehensible way for other programmers. here is some naming conventions for java programming language.

#### 1. Packages

Folders all in **lowercase**.

- java.util
- src.main.java
  
#### 2. Classes & Interfaces

Classes should be **noun** and in **PascalCase**.
Interfaces should be like classes.

> Avoid using Acronyms in naming classes and interfaces.

- class Car;
- class User;


#### 3. Methods

Methods should be **verbs** and write in **camelCase**.

- start();
- stop();
- getBackground();


#### 4. Variables

Variable names should be short yet meaningful and should not start with underscore _ or dollar sign $ characters
One-character variable names should be avoided except for temporary "throwaway" variables. Common names for temporary variables are i, j, k, m, and n for integers; c, d, and e for characters.
variables should be written in camelCase.

- int i;
- string inputText;