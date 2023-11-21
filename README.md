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
