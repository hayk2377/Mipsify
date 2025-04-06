**# Mipsify

Mipsify is an improved version of a Java to MIPS transpiler. This version includes enhanced features such as call stack tracking, support for functions, and loop handling. It is designed to efficiently convert Java code into MIPS assembly language, making it easier to understand and analyze low-level operations.

## Features

- **Java to MIPS Transpilation**: Converts Java code into MIPS assembly language.
- **Call Stack Tracking**: Provides detailed tracking of function calls and stack operations.
- **Function Support**: Handles function definitions and calls.
- **Loop Handling**: Supports various loop constructs in Java.

## Tech Stack

- **Programming Language**: Java
- **Transpilation Tools**: Custom Java to MIPS transpilation logic

## Installation

To get started with Mipsify, clone the repository and follow the instructions below to set up the environment and build the transpiler.

### Prerequisites

- Java Development Kit (JDK)

### Clone the Repository

"git clone https://github.com/hayk2377/Mipsify.git"
"cd Mipsify"

### Build the Transpiler

Run the following command to build the Mipsify transpiler:

"javac -d bin src/*.java"

## Usage

Once the transpiler is built, you can use it to transpile Java source files into MIPS assembly code.

### Transpile a Java Program

To transpile a Java program, use the following command:

"java -cp bin Mipsify path/to/your/file.java"

## Contributing

We welcome contributions to Mipsify! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License

This project is licensed under the MIT License.

## Contact

For any questions or suggestions, please feel free to open an issue or contact the repository owner.

---

Happy coding with Mipsify!
