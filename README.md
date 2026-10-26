
# CHARUSAT CEUE203 — OOPJ MiniBank Project

**Student Name:** Dwij Patel  
**Student ID:** 25CE077  
**University:** CHARUSAT — Charotar University of Science and Technology  
**Course:** CEUE203 — Object-Oriented Programming with Java  
**Semester:** 3  
**Java Version:** JDK 17 or later

---

## 1. Project Overview

MiniBank is a console-based banking application developed using Java. The project demonstrates Object-Oriented Programming (OOP) concepts through account management, banking transactions, validation, exception handling, file handling, collections, generic programming, and multithreading.

The repository contains an integrated MiniBank application along with individual practical implementations, Java source files, and supporting project resources.

## 2. Project Structure

```text
OOP_MiniBank/
├── README.md
├── oop-minibank-complete/
│   ├── src/
│   ├── test/
│   ├── bin/
│   ├── bin_test/
│   ├── MANIFEST.MF
│   ├── MiniBank.jar
│   └── README.md
└── Practicals/
    ├── Practical_01_MenuShell/
    ├── Practical_02_CustomerAndAccount/
    ├── Practical_03_ObjectMethodsAndNestedAddress/
    ├── Practical_04_ValidationAndCommandParsing/
    ├── Practical_05_InheritanceAndPolymorphism/
    ├── Practical_06_InterfacesPackagesAndJar/
    ├── Practical_07_AnnotationsAndReflection/
    ├── Practical_08_CustomExceptions/
    ├── Practical_09_MultithreadingAndSynchronization/
    ├── Practical_10_TransactionProcessingAndDeadlock/
    ├── Practical_11_FileHandlingAndReporting/
    ├── Practical_12_CollectionsAndAccountStore/
    └── Practical_13_GenericRepository/
```

### Directory Description

- **`oop-minibank-complete/`** — Contains the integrated MiniBank application.
- **`src/`** — Contains the Java source code.
- **`test/`** — Contains testing source files.
- **`bin/`** — Contains compiled application classes.
- **`bin_test/`** — Contains compiled test classes.
- **`MANIFEST.MF`** — Contains JAR manifest configuration.
- **`MiniBank.jar`** — Packaged Java application.
- **`Practicals/`** — Organizes the individual practical implementations.
- **`README.md`** — Provides project documentation.

## 3. Main Features

The project demonstrates the following banking features and Java concepts, as implemented in the source code:

- Menu-driven console interface.
- Customer and bank account management.
- Savings, current, and fixed-deposit account types.
- Deposit and withdrawal operations.
- Money transfer functionality.
- Account statements and reporting.
- Input validation and custom exceptions.
- Encapsulation, inheritance, and polymorphism.
- Abstract classes and interfaces.
- Collections and generic repositories.
- File handling and data persistence.
- Transaction processing.
- Multithreading and synchronization.
- Java packages and JAR packaging.

## 4. Technologies Used

- Java
- Object-Oriented Programming
- Java Collections Framework
- Exception Handling
- File Handling
- Generics
- Multithreading
- Command-Line Tools

## 5. System Requirements

- Java Development Kit (JDK) 17 or later.
- Windows Command Prompt or a Java-compatible IDE.
- Java commands configured in the system PATH.

Check the installed Java version:

```cmd
java -version
javac -version
```

## 6. Running the Integrated Application

### Step 1: Open the Project Directory

Open Command Prompt and navigate to the integrated project folder:

```cmd
cd /d E:\OOP_MiniBank\oop-minibank-complete
```

### Step 2: Start the Application

Run the packaged JAR file:

```cmd
java -jar MiniBank.jar
```

The application starts in the console if the JAR and its dependencies are configured correctly.

### Step 3: Run Demonstration Mode

The project also supports a demonstration mode through the following command:

```cmd
java -jar MiniBank.jar --demo
```

This executes the demonstration functionality implemented in the application.

## 7. Integrated Application Components

The integrated application contains classes and interfaces responsible for banking operations, account types, validation, transaction processing, data management, and utility functions.

Key components include:

- **`MiniBank.java`** — Main console application.
- **`PracticalDemos.java`** — Demonstration runner.
- **`Account.java`** — Account-related functionality.
- **`BankService.java`** — Banking service operations.
- **`TransactionProcessor.java`** — Transaction processing.
- **`AccountStore.java`** — Account storage functionality.
- **`Repository<T>`** — Generic repository functionality.
- **Exception classes** — Handle invalid banking operations.
- **Utility classes** — Support validation, reporting, logging, and file operations.

The source code defines the exact behavior of each component.

## 8. Learning Outcomes

Through this project, the following Java programming concepts are demonstrated:

- Designing classes and objects.
- Applying encapsulation, inheritance, and polymorphism.
- Using interfaces and abstract classes.
- Implementing input validation and exception handling.
- Working with collections and generic types.
- Performing file operations.
- Managing concurrent operations using multithreading and synchronization.
- Organizing Java applications into packages.
- Packaging and running Java applications using JAR files.

## 9. Conclusion

The MiniBank project demonstrates the practical application of Java and Object-Oriented Programming concepts through a structured, console-based banking system.

The individual practical directories organize the implementations, while the integrated application brings the banking functionality together in one project.

---

**Submitted by:** Dwij Patel  
**Student ID:** 25CE077  
**Course:** CEUE203 — Object-Oriented Programming with Java  
**University:** CHARUSAT
