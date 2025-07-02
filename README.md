# ft_printf 🎉

A custom implementation of the `printf` function in C, developed as part of the 42 curriculum. The goal of this project is to understand and replicate the behavior of the `printf` function, focusing on output formatting, type handling, and memory management.

## Features 🚀
- **Command Execution**: Using variadic functions to handle multiple data types.
- **Supported Format Specifiers**:
  - `%c`: Character
  - `%s`: String
  - `%d` / `%i`: Signed decimal integer
  - `%u`: Unsigned decimal integer
  - `%x` / `%X`: Unsigned hexadecimal integer
  - `%p`: Pointer address
- **Flags Handling**:
  - `-`: Left justify the output.
  - `0`: Pad the output with zeros instead of spaces.
  - `+`: Include a plus sign for positive numbers.
- **Width and Precision**:
  - Field width: Specify minimum width of output.
  - Precision: Control the number of digits after the decimal point or the maximum width of strings.
- **Memory Management**: Handle dynamic memory allocation efficiently.
- **Error Handling**: Properly manage errors, ensuring robust code.

## Installation & Usage 💻

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/ft_printf.git
    cd ft_printf
    ```

2. **Compile the Library**:
    ```bash
    make
    ```

3. **Test the Implementation**:
    After compiling, you can test your `ft_printf` function with your own code. Example:
    ```c
    #include "ft_printf.h"

    int main() {
        ft_printf("Hello, %s!\n", "World");
        ft_printf("Integer: %d\n", 42);
        return 0;
    }
    ```

4. **Run with Valgrind** (to check for memory leaks):
    ```bash
    make v
    ```

## How to Use 📌

- **Basic Example**:
    ```c
    ft_printf("Hello, %s!\n", "World");
    ```

- **Supported Commands**:
    - Print characters: `ft_printf("Character: %c\n", 'A');`
    - Print strings: `ft_printf("String: %s\n", "Hello!");`
    - Print integers: `ft_printf("Number: %d\n", 42);`
    - Print hexadecimals: `ft_printf("Hex: %x\n", 255);`

- **Exit with `Ctrl+D`** in your main terminal or shell.

## Built With 🛠️
- **C**: Standard C library and system calls.
- **Norminette Compliant**: The code follows 42's strict coding standards.
- **POSIX system calls**: `fork()`, `execve()`, `pipe()`, `dup2()`, `waitpid()`, etc.

## Authors ✨
- **[Your Name]** (GitHub: [Your GitHub Link])

## License 📜
This project is for educational purposes and follows 42 School's guidelines. All rights reserved.

🚀 **ft_printf**: Building a custom version of `printf` and understanding the low-level functionality behind it!
