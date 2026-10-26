# OOPJ Practical List — MiniBank (Practicals 1 to 14)
**Course**: CEUE203 — Object Oriented Programming with Java (Semester 3, 2026–27)  
**Institution**: CHARUSAT  
**Repository Naming Convention**: `oop-minibank-<rollno>`

## Project Overview
MiniBank is a layered Java 17+ banking application developed progressively across Practicals 1 through 14. It demonstrates records, enums, switch expressions, object-oriented encapsulation, inheritance & runtime polymorphism, functional interfaces & lambdas, custom annotations & reflection, checked custom exceptions, multithreading & synchronization, thread pools & deadlock prevention, Java NIO file persistence & reporting, the Collections Framework, generic repositories, and JUnit 5 testing.

## Package & Directory Structure
```text
oop-minibank-complete/
├── MANIFEST.MF
├── MiniBank.jar                              # Pre-built runnable JAR (Main-Class: MiniBank)
├── README.md
├── src/
│   ├── MiniBank.java                         # Main CLI entry point (Practical 1 & 14)
│   ├── PracticalDemos.java                   # Automated runner verifying Practicals 1 to 14
│   ├── exception/                            # Practical 8: Checked custom exceptions
│   │   ├── BankException.java
│   │   ├── InsufficientFundsException.java
│   │   ├── AccountNotFoundException.java
│   │   └── InvalidAmountException.java
│   ├── model/                                # Practicals 1, 2, 3, 4, 5, 6, 11, 12
│   │   ├── Account.java
│   │   ├── BankInfo.java
│   │   ├── Command.java
│   │   ├── CurrentAccount.java
│   │   ├── Customer.java                     # Includes static nested Customer.Address & clone()
│   │   ├── FixedDepositAccount.java
│   │   ├── InterestBearing.java
│   │   ├── MenuOption.java
│   │   ├── Premium.java
│   │   ├── SavingsAccount.java
│   │   ├── Transactable.java
│   │   ├── TransactionType.java
│   │   ├── WithdrawRule.java
│   │   └── annotation/                       # Practicals 7 & 14: Custom runtime annotations
│   │       ├── Audit.java
│   │       ├── Id.java
│   │       ├── MaxLength.java
│   │       └── Positive.java
│   ├── service/                              # Practicals 9, 10, 12, 13, 14
│   │   ├── AccountStore.java
│   │   ├── AccountWorker.java
│   │   ├── BankService.java
│   │   ├── Repository.java
│   │   └── TransactionProcessor.java
│   └── util/                                 # Practicals 4, 7, 8, 11, 14
│       ├── AccountFileStore.java
│       ├── AnnotationValidator.java
│       ├── AuditLogger.java
│       ├── AuditSession.java
│       ├── CommandParser.java
│       ├── ReportGenerator.java
│       ├── StatementFormatter.java
│       ├── TransactionLogger.java
│       └── Validator.java
└── test/
    └── BankServiceTest.java                  # Practical 14: JUnit 5 @Test suite
```

## Quick Start Commands (JDK 17+)

### 1. Run the Pre-built Runnable JAR
```bash
# Launch the interactive MiniBank menu:
java -jar MiniBank.jar

# Run all 14 Practical Expected-Result Demonstrations automatically:
java -jar MiniBank.jar --demo
```

### 2. Compile from Source and Build `MiniBank.jar`
```bash
mkdir -p bin
javac -d bin $(find src -name "*.java")
jar cfm MiniBank.jar MANIFEST.MF -C bin .
java -jar MiniBank.jar
```

### 3. Compile and Run JUnit 5 Tests (`BankServiceTest`)
```bash
mkdir -p bin_test
javac -cp bin -d bin_test $(find test -name "*.java")
java -cp bin:bin_test BankServiceTest
```
