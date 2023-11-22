# CapaCiTi-Java-Intro

Java is a programming language that allows developers to write instructions for computers. These instructions, written in Java, can run on different devices or systems, thanks to a special software called the Java Virtual Machine (JVM). Java is known for its simplicity, versatility, and the ability to create software that works on various platforms.

## Java Code (.java):

Java code is the source code that you write in the Java programming language. It's a human-readable text file with a .java extension. This code contains instructions that define how a Java program should behave.

```
// Simple program to add two numbers
public class AddNumbers {
    public static void main(String[] args) {
        int num1 = 5;
        int num2 = 10;
        int sum = num1 + num2;
        System.out.println("Sum: " + sum);
    }
}

```

## Javac Compiler:

The javac compiler is part of the Java Development Kit (JDK). It translates the human-readable Java source code (.java files) into a lower-level, platform-independent bytecode.

Example:
After writing the AddNumbers.java code, you compile it using the javac command:

```
javac AddNumbers.java
```
This produces a file named AddNumbers.class, containing bytecode.

## Bytecode:

Bytecode is an intermediate representation of the Java code. It's a set of instructions that can be executed by the Java Virtual Machine (JVM). Bytecode is platform-independent, meaning it can be run on any device with a JVM.

## Java Virtual Machine (JVM):

The JVM is a virtual machine that executes Java bytecode. It translates the bytecode into machine-specific instructions at runtime. This allows Java programs to be "write once, run anywhere," as long as a JVM is available for the target platform.

Example:
After compiling AddNumbers.java, you run it using the java command:

```
java AddNumbers
```
The JVM reads the AddNumbers.class bytecode file and executes the program, producing the output.

## Java Development Kit (JDK):

The JDK is a software development kit that includes the tools needed for Java development. It includes the javac compiler, the java runtime, and other development tools.

Example:
When you download and install the JDK, you gain access to tools like javac for compiling Java code and java for running Java programs.

In summary, you write Java code, use the javac compiler to convert it into bytecode, and then run it on the Java Virtual Machine (JVM). The Java Development Kit (JDK) provides the necessary tools for these tasks.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Typical Structure of a Java program

1.    Package Declaration:

A package declaration is used to organize classes into a specific namespace.
Example: package com.example.myproject;
Import Statements:

2.    Import statements bring in classes or packages from other namespaces.
Example: import java.util.ArrayList;
Comments:

3.    Comments provide non-executable text to document code.
Example:

```
// This is a single-line comment

/* 
   This is a
   multi-line comment
*/

```
4.    Class Definition:

Class definition outlines the blueprint for creating objects.
Example:
```
public class Car {
   // Class members go here
}

```
5    Attributes:

Attributes represent the characteristics or data members of a class.
Example:
```
public class Car {
   String model;
   int year;
}

```
6    Methods/Behaviours:

Methods define the actions or behaviors of a class.
Example:

```
public class Car {
   void startEngine() {
       // Code to start the engine
   }
   
   void drive() {
       // Code for driving the car
   }
}

```

### These elements collectively contribute to the structure and functionality of a Java program, promoting code organization, reusability, and readability.

## What is a variable?

A variable is a name given to a memory location. It is the basic unit of storage in a program.
The value stored in a variable can be changed during program execution.
A variable is only a name given to a memory location; all the operations done on the variable effects that memory location.
In Java, all the variables must be declared before use.

## How to declare variables?

"type": Type of data that can be stored in this variable = integer(int).
"name": Name given to the variable = num.
In this way, a name can only be given to a memory location. It can be assigned values in two ways:

Variable Initialization
Assigning value by taking input EG BELOW

```
int num = 1;
```

value: It is the initial value stored in the variable.

Declaring variables examples:

-    float simpleInterest; - Declaring float variable
-    int myAge = 19; - Declaring and Initializing integer variable
-    char firstLetter = 'h'; - Declaring and Initializing character variable

## There are three types of variables in Java:

### Local Variables:

Local variables are declared within a specific method or block and exist only for the duration of that method or block.
```
void exampleMethod() {
    int localVar = 10; // localVar is a local variable
    // Other code here
}

```

### Instance Variables:

Instance variables are declared in a class but outside any method. They exist as long as the object of the class exists.
Example:

```
public class MyClass {
    int instanceVar; // instanceVar is an instance variable
}

```

### Class (Static) Variables:

Class variables, declared with the static keyword, belong to the class rather than any particular instance. They are shared among all instances of the class.
Example:

```
public class MyClass {
    static int classVar; // classVar is a class variable
}

```
### These variable types serve different purposes in Java and have different scopes and lifetimes. Local variables are confined to a specific method, instance variables belong to an instance of a class, and class variables are shared among all instances of a class.


# Java Datatype

In Java, a data type is a classification that specifies which type of value a variable can hold. Java has two main categories of data types: primitive data types and reference data types.

## Primitive Data Types:

### int: 
Used for integer values (e.g., 1, 42, -10).
### double: 
Used for floating-point numbers (e.g., 3.14, -0.5, 2.0).
#### char: 
Used for a single character (e.g., 'a', '1', '@').
### boolean: 
Used for true/false values (e.g., true, false).
## byte: 
Used for small integers (usually used in file I/O operations).
### short: 
Similar to int, but with a smaller range of values.
### long: 
Used for larger integer values, followed by "L" or "l" (e.g., 100000L).

## Reference Data Types:

### Objects: Instances of classes that you create in your code.
### Arrays: Ordered collections of values of the same type.

Example: 
```
public class Example {
    public static void main(String[] args) {
        // Primitive data types
        int age = 25;
        double salary = 50000.5;
        char grade = 'A';
        boolean isStudent = true;

        // Reference data types
        String name = "John Doe"; // String is a class in Java
        int[] numbers = {1, 2, 3, 4, 5}; // Array of integers
    }
}
```

In the example above:

-    age, salary, grade, and isStudent are variables with primitive data types.
-    name is a variable with a reference data type (String).
-    numbers is a variable with a reference data type (array of integers).

### Understanding and using the appropriate data type is essential for efficient and correct programming in Java.
