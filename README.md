Campus Course & Records Manager (CCRM) 
A comprehensive console-based Java application for managing student, course, and grade records in educational institutions. This project was developed as a submission for the "Programming in Java" course at Vellore Institute of Technology (VIT).


Name: Kaushtubh

Registration Number: 24BCE11277

## Key Features
Student Management: Create, update, and manage student profiles.

Course Management: Add, search, and list courses; assign instructors.

Grades & Transcripts: Record grades, compute GPA, and generate official transcripts.

Data Handling: Import/export student and course data via CSV files.

Backup System: Create timestamped backups of all academic data.

## Technical Implementation
This project demonstrates a deep understanding of core and advanced Java concepts, including:

Object-Oriented Programming (OOP): Applied principles of Encapsulation, Inheritance, Polymorphism, and Abstraction to create a modular and scalable codebase.

Design Patterns: Implemented Singleton for configuration management and the Builder pattern for object creation.

Modern Java Features: Leveraged Stream API, Lambda Expressions, NIO.2 (Path API) for efficient file operations, and the Date/Time API.

Robust Error Handling: Utilized custom exceptions to manage business logic violations and improve application stability.

For a detailed mapping of syllabus topics to code implementation, see the Syllabus Mapping section below.

## Getting Started
Prerequisites
Java JDK 11 or higher

A Java IDE (e.g., Eclipse, IntelliJ IDEA)

Installation & Setup
Clone the repository:

Bash

git clone https://github.com/kaushtubh0134/CCRM
cd CCRM
Verify Java Installation:

Bash

java -version
javac -version
If not installed, follow the official Oracle JDK installation guide.

How to Run
There are two primary ways to run the application:

1. From the Command Line
Compile and run the main application class. The -ea flag is recommended to enable assertions for debugging purposes.

Bash

# Compile
javac -cp src src/edu/ccrm/cli/CCRMApplication.java

# Run
java -ea -cp src edu.ccrm.cli.CCRMApplication
2. Using an IDE (e.g., Eclipse)
Open Eclipse and go to File -> Import -> Existing Projects into Workspace.

Select the CCRM project folder.

Right-click on CCRMApplication.java in the Project Explorer.

Select Run As -> Java Application.

## Project Documentation
Java Platform & Architecture
This section provides a brief overview of the Java ecosystem.

Java Architecture
Java code is compiled into bytecode (.class files) by the javac compiler. This bytecode is then executed by the Java Virtual Machine (JVM), which translates it into machine code for the specific operating system. This is the foundation of the "Write Once, Run Anywhere" philosophy.

JVM (Java Virtual Machine): The abstract machine that executes the bytecode.

JRE (Java Runtime Environment): Includes the JVM, core libraries, and other files required to run a Java application.

JDK (Java Development Kit): The complete development kit for Java, including the JRE and all necessary development tools (e.g., javac, jar).

Feature	Java SE (Standard Edition)
Target Platform	Desktop applications, standalone apps
APIs Included	Complete Java core APIs
Deployment	Desktop JAR/EXE files

Export to Sheets
Syllabus Mapping
Syllabus Topic	Implementation Location	Description
OOP Principles	edu.ccrm.domain.*	Person hierarchy, encapsulation, polymorphism.
Design Patterns	AppConfig.java, Course.Builder	Singleton, Builder.
Exception Handling	edu.ccrm.domain.exceptions.*	Custom checked/unchecked exceptions.
File I/O (NIO.2)	edu.ccrm.io.*	Path API, Files operations.
Stream API	StudentService.getStatistics()	Filter, map, reduce operations.
Lambda Expressions	Service search methods	Predicates, comparators.
Date/Time API	Domain classes	LocalDate, DateTimeFormatter.

Export to Sheets
## License & Acknowledgments
This project is for academic purposes. It was developed using resources from:

Official Java Documentation

"Gang of Four" Design Patterns reference

Discussions on Java 8+ functional programming

Project Completed: September 2025
Academic Session: Semester 3, B.Tech Computer Science







