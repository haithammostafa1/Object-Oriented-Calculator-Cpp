# Object-Oriented Calculator (C++) 🧮

A robust calculator application developed using **Object-Oriented Programming (OOP)** principles in C++. Unlike simple calculators, this project maintains a "State", allowing it to keep track of results, previous operations, and even undo the last action.

## 🌟 Key Features
- **Core Operations**: Addition, Subtraction, Multiplication, and Division.
- **Safety First**: Includes a private helper function `_IsZero()` to prevent division by zero errors.
- **State Management**: Keeps track of the `_LastOperation`, `_LastNumber`, and `_PreviousResult`.
- **Undo Capability**: The `CancelLastOperation()` method allows reverting the current result to the previous state.
- **Memory Clear**: A `Clear()` method to reset the calculator entirely.

## 🛠️ OOP Concepts Applied
- **Classes & Objects**: The entire logic is encapsulated within the `clsCalculator` class.
- **Access Modifiers**: 
  - **Private**: Data members (Result, LastNumber, etc.) are hidden to prevent direct external interference.
  - **Public**: Methods provided as an interface for the user to interact with the calculator.
- **Data Integrity**: Ensures that the internal state is only modified through validated methods.

