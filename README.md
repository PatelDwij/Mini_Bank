
# CHARUSAT CEUE203 — OOPJ MiniBank Project

**Student Name:** Dwij Patel  
**Student ID:** 25CE077  
**University:** CHARUSAT — Charotar University of Science and Technology  
**Course:** CEUE203 — Object-Oriented Programming with Java  
**Semester:** 3  
**Java Version:** JDK 17 or later

---

## 1. Project Overview

MiniBank is a console-based banking application developed using Java. It demonstrates Object-Oriented Programming concepts through account management, banking transactions, validation, exception handling, file handling, collections, generic programming, and multithreading.

This project contains:

- An integrated MiniBank application.
- Separate practical folders for Practical 1 to Practical 13.
- Java source code and compiled application files.
- A runnable JAR file.
- Separate testing source files.

**Faculty Instruction:** Practical 14, which covers JUnit Framework Testing, is excluded from the practical record because it is not included in the syllabus. The integrated MiniBank project is maintained separately.

## 2. What's Inside This Project

### A. `oop-minibank-complete/`

This folder contains the integrated MiniBank application.

```text
oop-minibank-complete/
├── bin/
├── bin_test/
├── src/
├── test/
├── MANIFEST.MF
├── MiniBank.jar
└── README.md
```

**Folder descriptions:**

- `src/` — Java source code for the integrated application.
- `bin/` — Compiled application classes.
- `bin_test/` — Compiled test classes.
- `test/` — Separate testing source files.
- `MANIFEST.MF` — JAR manifest configuration.
- `MiniBank.jar` — Packaged Java application.
- `README.md` — Documentation specific to the integrated application.

#### Main Source Code

The integrated source code includes classes and interfaces for banking operations, account types, validation, transactions, and data management.

The project includes components such as:

- `MiniBank.java` — Main console application.
- `PracticalDemos.java` — Demonstration and verification runner.
- `Account.java` and specialized account classes.
- `BankService.java` — Banking service operations.
- `TransactionProcessor.java` — Transaction processing.
- `AccountStore.java` and `Repository<T>` — Account storage and generic repository functionality.
- Utility classes for validation, statements, logging, and file handling.
- Custom exception classes for handling invalid banking operations.

The exact functionality is defined by the source code included in the project.

### B. `Practicals/`

This folder contains the individual practical implementations from Practical 1 to Practical 13.

```text
Practicals/
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

These folders preserve the individual stages of the MiniBank practical work.

**Practical 14 is intentionally excluded from this directory** in accordance with the faculty announcement.

### C. Root `README.md`

This file documents the complete project structure, application overview, and submission information.

## 3. Main Features

The integrated MiniBank application demonstrates the following concepts, according to their implementation in the source code:

- Menu-driven console application.
- Customer and bank account management.
- Savings, current, and fixed-deposit account types.
- Deposit, withdrawal, and money transfer operations.
- Account statements and reporting.
- Input validation and custom exceptions.
- Encapsulation, inheritance, and polymorphism.
- Interfaces and abstract classes.
- Collections and generic repositories.
- File handling and data persistence.
- Transaction processing.
- Multithreading and synchronization.
- Java packages and runnable JAR packaging.

## 4. Requirements

- Java Development Kit (JDK) 17 or later.
- Windows Command Prompt or a Java-compatible IDE.
- `java` and `javac` available in the system PATH.

Check the installed Java version:

```cmd
java -version
javac -version
```

## 5. How to Run the Integrated Application

### Step 1: Open the project directory

Open Command Prompt and run:

```cmd
cd /d E:\OOP_MiniBank\oop-minibank-complete
```

### Step 2: Run the JAR

Run the packaged application:

```cmd
java -jar MiniBank.jar
```

If the JAR is configured correctly, the MiniBank console menu will appear.

Follow the menu instructions to use the available banking operations.

### Step 3: Run the demonstration mode

If supported by the included application, use:

```cmd
java -jar MiniBank.jar --demo
```

This runs the demonstration mode implemented by the project.

## 6. Testing Information

The integrated project includes a separate `test/` directory.

The faculty has instructed students not to include Practical 14 in the practical record because JUnit Framework Testing is outside the syllabus.

The supplied test directory contains project-local compatibility classes. These should not be described as the official JUnit 5 library.

The separate test files are not required to be included in the practical record. Their presence does not mean that Practical 14 must be added to the practical file.

## 7. Practical Organization

The `Practicals/` directory contains individual implementations for Practical 1 through Practical 13.

The `oop-minibank-complete/` directory contains the integrated application, combining the implemented banking features into one project.

The practical folders and integrated application are maintained separately for easier organization and review.

## 8. Submission Guidelines

- Keep the integrated application in `oop-minibank-complete/`.
- Retain Practical 1 to Practical 13 as required for the practical record.
- Do not include Practical 14 in the practical file, as instructed by the faculty.
- Keep the root README consistent with the actual project structure.
- Include the GitHub repository link when required.
- Submit the final project ZIP according to the faculty's instructions.
- Avoid unnecessary duplicate projects and temporary build files.

## 9. Conclusion

The MiniBank project demonstrates how Java and Object-Oriented Programming concepts can be applied to develop a structured, console-based banking application.

The individual practical folders organize the practical work, while the integrated MiniBank application combines the implemented features into a single project.

---

**Submitted by:** Dwij Patel  
**Student ID:** 25CE077  
**Course:** CEUE203 — Object-Oriented Programming with Java  
**University:** CHARUSAT
