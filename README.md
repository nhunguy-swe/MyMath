# MyMath - TDD Practice 

A C# library project focused on practicing **Test-Driven Development (TDD)** and algorithm optimization.

## Tech Stack
* **Language:** C# (.NET Core)
* **Testing Framework:** NUnit / MSTest
* **Tool:** Visual Studio Test Explorer

## Development Workflow (TDD)
I followed the **Red-Green-Refactor** cycle to develop the `SquareRoot` method:
1. **Red:** Wrote unit tests before implementing any logic.
2. **Green:** Implemented the minimum code necessary to pass the tests.
3. **Refactor:** Optimized the algorithm using the **Newton-Raphson** method while ensuring all tests remained passing.

## Testing Scenarios
* **Value Range:** Verified the algorithm across a broad range of inputs from $1e^{-8}$ to $1e^{+8}$.
* **Error Handling:** Handled negative inputs by throwing an `ArgumentOutOfRangeException`.
* **Code Coverage:** Ensured all logic paths and decision points were exercised by unit tests.

## How to Run
1. Open the `.sln` file in **Visual Studio**.
2. Open **Test Explorer** (`Ctrl + E, T`).
3. Click **Run All** (`Ctrl + R, A`) to execute the test suite.

---
*This project was developed as a hands-on exercise in Software Quality Assurance and TDD principles.*
