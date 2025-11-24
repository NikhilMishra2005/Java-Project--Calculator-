# Java Swing Calculator

A simple GUI calculator application built using Java, AWT, and Swing.  
It supports basic arithmetic operations and percentage, sign toggle, and square root functions with an interface inspired by modern mobile calculators. [web:27][web:36]

## Features

- Perform addition, subtraction, multiplication, and division. [web:27][web:36]  
- Support for percentage (%) operation. [web:36][web:40]  
- Toggle sign of the current value (+/-). [web:36][web:40]  
- Calculate square root (√) of the displayed number. [web:36][web:40]  
- Clear all input using AC button. [web:33][web:36]  
- Responsive button layout using `GridLayout` and colored buttons using custom `Color` objects. [web:24][web:41]

## Technologies Used

- Java (JDK 8+ recommended). [web:32][web:34]  
- Java Swing for GUI components (`JFrame`, `JPanel`, `JButton`, `JLabel`). [web:11][web:24]  
- AWT for layout managers (`BorderLayout`, `GridLayout`) and event handling (`ActionListener`). [web:11][web:24]

## Project Structure

[web:27][web:33]  
3. Open the project in your IDE (VS Code with Java Extension Pack, IntelliJ IDEA, Eclipse, etc.). [web:24][web:32]  
4. Make sure the `package` structure matches your folder structure (`net.firstproject.java`). [web:32][web:34]  
5. Run `Calculator.java` as a Java application; the calculator window should appear. [web:27][web:36]

## Usage

- Click number buttons to input values. [web:33][web:36]  
- Use `+`, `-`, `×`, `÷` to choose an operation, then press `=` to see the result. [web:27][web:40]  
- Use `%` to convert the current value into a percentage. [web:36][web:40]  
- Use `+/-` to toggle between positive and negative. [web:36][web:40]  
- Use `√` to calculate the square root of the current value. [web:36][web:40]  
- Press `AC` to reset the calculator. [web:33][web:36]

## Future Improvements

- Add keyboard support for number and operator keys. [web:36][web:40]  
- Improve error handling (e.g., division by zero, invalid input). [web:36][web:37]  
- Add more scientific functions (trigonometry, powers, memory, etc.). [web:30][web:36]  
- Write unit tests for core calculation logic. [web:28][web:34]

## License

You can add a license section here (for example, MIT License) or link to a `LICENSE` file in the repository. [web:34][web:29]
