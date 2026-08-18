# Java Architecture & Installation

## 1. JDK vs JRE vs JVM

### JDK — Java Development Kit

The JDK is used to develop Java applications. It provides the tools needed to write, compile, debug, and run Java programs.

**JDK = Development tools + JRE**

### JRE — Java Runtime Environment

The JRE provides the environment required to run Java applications. It contains the JVM and the libraries needed for running Java programs.

**JRE = JVM + Java libraries**

### JVM — Java Virtual Machine

The JVM is responsible for executing Java bytecode. It acts as the runtime engine that allows Java programs to run on different operating systems.

**JVM = Executes bytecode**

---

## 2. Bytecode

Java source code is written in a `.java` file.

The Java compiler (`javac`) compiles the source code into **bytecode**, which is stored in a `.class` file.

The JVM then reads and executes this bytecode.

**Flow:**

`.java` → Java Compiler (`javac`) → `.class` bytecode → JVM → Program execution

---

## 3. Why Java is Platform Independent

Java is platform independent because Java source code is compiled into **bytecode**, rather than directly into machine-specific code.

The same bytecode can run on different operating systems as long as a compatible JVM is available.

**Write Once, Run Anywhere.**

---

## 4. My Key Takeaways

- JDK is used to develop Java programs.
- JRE provides the environment needed to run Java programs.
- JVM executes Java bytecode.
- Java source code is compiled into platform-independent bytecode.
- The JVM allows the same bytecode to run on different operating systems.
