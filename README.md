# FactoryMethod

## Overview

This project demonstrates the Factory Method design pattern in Java. The Factory Method pattern provides a way to delegate the instantiation logic to subclasses, allowing for more flexible and reusable code.

## Table of Contents

- [Getting Started](#getting-started)
- [Factory Method Pattern Explanation](#factory-method-pattern-explanation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

To get started with this project, clone the repository and ensure you have Java installed.

### Prerequisites

- Java Development Kit (JDK) 8 or higher

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/luanmxz/FactoryMethod.git
    ```
2. Navigate to the project directory:
    ```bash
    cd FactoryMethod
    ```

## Factory Method Pattern Explanation

The Factory Method pattern defines an interface for creating an object but allows subclasses to alter the type of objects that will be created. This pattern is particularly useful for cases where the exact type of object might vary.

### Classes Included

- **ButtonInterface**: The common interface for all button types.
- **Dialog**: Abstract class declaring the factory method.
- **HTMLButton**: Concrete implementation of `ButtonInterface` for HTML buttons.
- **HTMLDialog**: Concrete implementation of `Dialog` for HTML dialogs.
- **WindowsButton**: Concrete implementation of `ButtonInterface` for Windows buttons.
- **WindowsDialog**: Concrete implementation of `Dialog` for Windows dialogs.

## Usage

You can run the provided examples to see the Factory Method pattern in action.

### Example

To run the test for the Factory Method pattern:
```bash
javac FactoryMethodTest.java
java FactoryMethodTest
```

## Contributing

Contributions are welcome! Please fork the repository and submit pull requests for any improvements or additional patterns you would like to add.

### Steps to Contribute

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
