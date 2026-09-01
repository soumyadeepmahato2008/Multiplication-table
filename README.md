# Multiplication_table
A simple C program that generates the multiplication table of a user-defined number. This beginner-friendly project demonstrates user input, loops, arithmetic operations, and formatted output in C. Ideal for students learning iterative programming concepts and practicing basic mathematical computations using the C programming language.

Multiplication Table in C

A simple C program that generates the multiplication table of a number entered by the user. This beginner-friendly project helps learners understand loops, user input, arithmetic operations, and formatted output in C programming.

📌 About

This program:

- Accepts a number from the user.
- Generates its multiplication table.
- Displays the table from 1 to 10.
- Demonstrates the use of loops and arithmetic operations in C.

📂 Project Structure

Multiplication_Table/
├── multiplication_table.c
└── README.md

💻 Sample Code

#include <stdio.h>

int main() {
    int num;

    printf("Enter a number: ");
    scanf("%d", &num);

    printf("\nMultiplication Table of %d\n", num);

    for(int i = 1; i <= 10; i++) {
        printf("%d x %d = %d\n", num, i, num * i);
    }

    return 0;
}

🚀 How to Compile and Run

Using GCC

Compile the program:

gcc multiplication_table.c -o table

Run the program:

Linux/macOS

./table

Windows

table.exe

📤 Sample Output

Enter a number: 5

Multiplication Table of 5

5 x 1 = 5
5 x 2 = 10
5 x 3 = 15
5 x 4 = 20
5 x 5 = 25
5 x 6 = 30
5 x 7 = 35
5 x 8 = 40
5 x 9 = 45
5 x 10 = 50

🛠 Requirements

- GCC Compiler or any C Compiler
- Terminal / Command Prompt
- Basic knowledge of C programming

📚 Concepts Used

- Variables and Data Types
- User Input ("scanf")
- Output ("printf")
- "for" Loop
- Arithmetic Operations

🎯 Learning Objectives

By completing this project, you will learn:

- How to use loops in C
- How to take user input
- How to perform multiplication operations
- How to display formatted output

🔮 Future Enhancements

- Generate tables up to a user-defined range
- Print tables for multiple numbers
- Create a menu-driven math utility
- Save output to a file

📄 License

This project is open-source and available under the MIT License.

---

⭐ If you found this project helpful, consider giving it a star on GitHub!
