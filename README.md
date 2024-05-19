#### This project is for the Devops bootcamp exercise for 
#### "Build Tools and Package Managers" 


# Project Setup and Execution Documentation

## Introduction
This document outlines the steps I took to set up, modify, and execute a Java project. It covers cloning a project repository, handling build errors, testing, and running the application with parameters.

## Exercise 0: Clone Project and Create Own Git Repository

Initially, I cloned an existing project from a specified source repository. Following this, I created my own Git repository to maintain the changes and progression of my project work separately.

## Exercise 1: Build Jar Artifact

During my first attempt to build a jar file using Gradle, I encountered a compile error within a test that prevented the build from completing successfully. This issue was due to a compile-time error in the test scripts.

## Exercise 2: Run Tests

To resolve the compile error, I modified a test case by changing a "true" string to a boolean true. After making this change, I executed the tests using the `gradle test` command to ensure that all tests passed, confirming the fix.

## Exercise 3: Clean and Build App

With the tests fixed, I proceeded to clean the build folder using `gradle clean`. Subsequently, I attempted the jar file build again, which this time completed without errors.

## Exercise 4: Start Application

After successfully building the jar file, I started the application using the command `java -jar build/libs/app-1.0.jar` (note: `app-1.0.jar` should be replaced with the actual name of your jar file). This step was crucial to verify that the application ran smoothly as a standalone jar file.

## Exercise 5: Start App with 2 Parameters

To enhance the application's functionality, I added parameter input handling in the Java code. I included a code snippet that logs two parameters passed to the application. After modifying the code, I rebuilt the jar file and executed it again, this time with two parameters to test the new functionality.

## Conclusion

The project setup and execution were carried out meticulously, addressing initial setbacks such as build errors and enhancing the application's capabilities by introducing parameter inputs. Each step was documented to assist in troubleshooting and future modifications.
