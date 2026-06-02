# Java Architecture

## 1. Java Execution Process:

* Source Code: Java code is written in a .java file, which is human-readable.

* Compilation: The Java compiler (javac) compiles the source code into Byte Code (.class file), not machine code.

* Execution: The Java Virtual Machine (JVM) executes the byte code. Java is platform-independent because the same byte code can run on any operating system that has a JVM installed.

## 2. Java Architecture Components:

* JDK (Java Development Kit): A bundle that includes the JRE and development tools (like the compiler javac) required to create and run Java applications.

* JRE (Java Runtime Environment): Provides the environment for running Java programs. It includes the JVM, core libraries, and other components.

* JVM (Java Virtual Machine): The core component that converts byte code into machine-specific code at runtime.

# 3. Detailed Execution Workflow:

* Compile Time: Source code is transformed into byte code.
Runtime:

* Class Loader: Loads the class files into memory.

* Byte Code Verifier: Ensures the code is safe and valid.

* Interpreter: Executes the byte code line by line.

* JIT (Just-In-Time) Compiler: Optimizes performance by compiling frequently used code blocks (methods/functions) into machine code, preventing repetitive interpretation.

## 4. Tools and Installation:

* JDK: Essential for development. Downloadable from the official Oracle website.

* IDE: IntelliJ IDEA (Community Edition is free) is recommended as the tool for writing, managing, and running Java code.