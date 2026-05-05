# MyMath: Test-Driven Development (TDD) Demo

A C# Class Library project focused on mathematical operations, developed using the **Test-Driven Development (TDD)** methodology and **Visual Studio Test Explorer**.

## Project Overview
This project serves as a practical demonstration of how to develop robust code through incremental changes and continuous testing. It follows the "Red-Green-Refactor" cycle to implement mathematical functions like square root calculation with high precision.

## Features
- **SquareRoot Calculation:** Implementation of a custom square root algorithm.
- **Input Validation:** Robust handling of exceptional cases, such as negative inputs, using `ArgumentOutOfRangeException`.
- **High Precision:** Logic designed to maintain accuracy across a broad range of input values (from $1e^{-8}$ to $1e^{+8}$).

## TDD Workflow Applied
This repository showcases the following professional development steps:
1.  **Create a Test:** Writing a test for a method before the method actually exists.
2.  **Generate Code:** Using Visual Studio's IntelliSense to generate stubs for types and methods directly from the test code.
3.  **Run & Fail:** Verifying the test fails initially (Red).
4.  **Verify Code Change:** Implementing the simplest code to make the test pass (Green).
5.  **Extend & Refactor:** Adding tests for boundary cases and refactoring the algorithm for better performance without changing its behavior.

## How to Run Tests
1.  **Open the Solution:** Load `MyMath.sln` in Visual Studio.
2.  **Access Test Explorer:** Go to `Test > Windows > Test Explorer`.
3.  **Execute:** Click **Run All**.
4.  **Analyze:** View the **Test Detail Summary** to inspect stack traces or failure messages for any failing tests.

## Testing Methodology
- **Range Testing:** Using loops to verify the algorithm against a wide spectrum of inputs.
- **Exceptional Cases:** Utilizing `try-catch` blocks and `Assert.Fail()` to ensure the code handles invalid data correctly.
- **Refactoring Safety:** Using existing tests as a safety net to ensure that performance optimizations do not introduce new bugs.

---
*Developed following Microsoft's "Walkthrough: Test-driven development using Test Explorer".*
