# Password Generator

## Project Description
A Java-based **Password Generator** that allows users to create secure, customizable passwords. It supports character type selection (lowercase, uppercase, numbers, symbols) and custom characters. Password strength is evaluated using the **zxcvbn** library.

## Key Features
- **Random Password Generation**: Generates a password based on user-defined criteria.
- **Password Strength Evaluation**: Uses **zxcvbn** to provide a strength score (0-4).
- **Customization**: Choose character types and add custom characters.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Password-generator.git
    ```
2. Navigate to the project folder:
    ```bash
    cd Password-generator
    ```
3. Compile and run the Java program using your IDE or command line.

## Usage
1. Run the program.
2. Provide your desired password length and select character types.
3. The program will generate a password and show its strength.

## Challenges
- Ensuring randomness and password security.
- Integrating **zxcvbn** for accurate strength evaluation.
- Validating user input.

## Improvements
- Added **custom character set** for greater flexibility.
- Better feedback for password strength.

## Input/Output
- No external files used. The program works through the console.

## Conclusion
The **Password Generator** provides a simple way to create strong, customizable passwords with built-in strength evaluation.

---

### License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
