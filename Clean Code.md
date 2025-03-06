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
variables should be written in caint daysSinceCreation;
melCase.

- int i;
- string inputText;






### Naming

#### 1. Intention-Revealing names

No need to comment for responsibility

- int d; // elapsed time in days (WRONG)
- int elapsedTimeInDays;
- int daysSinceCreation;

```java
public List<int[]> getThem() {
 List<int[]> list1 = new ArrayList<int[]>();
 for (int[] x : theList)
    if (x[0] == 4)
        list1.add(x);
 return list1;
 }
 ```

 ```java
 public List<int[]> getFlaggedCells() {
    List<int[]> flaggedCells = new ArrayList<int[]>();
    for (int[] cell : gameBoard)
        if (cell[STATUS_VALUE] == FLAGGED)
        flaggedCells.add(cell);
    return flaggedCells;
 }
 ```


 #### 2. Pronounceable names

 If you can’t pronounce it, you can’t discuss it without sounding like an idiot. So make your names pronounceable!

 - arr
 - tbl
 - class DtaRcrd102


#### 3. Similarity

Pick one word for one abstract concept and stick with it.
Avoid using the same word for two purposes.

- fetch()
- retrieve()
- get()

- add()