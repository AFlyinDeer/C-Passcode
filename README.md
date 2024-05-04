# Passcode Finder

## Overview

**Passcode Finder** is a C++ program designed to find the shortest passcode based on a series of successful login attempts. The program utilizes backtracking as a method to identify the shortest possible password from a file containing 50 successful login attempts.

## Features

- **Backtracking Algorithm**: The program employs a backtracking algorithm to explore all possible combinations of digits and identify the shortest passcode.
- **Input Validation**: Secure coding practices are employed to validate input when opening a file, helping to prevent buffer overflow vulnerabilities.
- **C Strings**: The program utilizes C-style strings for efficient handling of character data.
- **Modern C++ Practices**: Modern C++ practices are employed, including the use of `<iostream>` for input/output operations.

## Functionality

The program reads login attempts from a file named `keylog.txt`. It then identifies unique digits present in the login attempts and initiates the backtracking process from each unique digit. The backtracking algorithm explores the possible combinations of digits, considering the order of appearance in the login attempts, and determines the shortest passcode. Finally, the program outputs the shortest passcode found.

## Usage

To use the Passcode Finder:

1. Compile the source code using a C++ compiler.
2. Ensure the file `keylog.txt` containing the successful login attempts is present in the same directory as the executable.
3. Run the compiled executable.
4. The program will output the shortest passcode discovered.

## Getting Started

To compile and run the program, ensure you have a C++ compiler installed on your system. Follow these steps:

1. Clone the repository or download the source code files.
2. Open a terminal or command prompt and navigate to the directory containing the source code files.
3. Compile the source code using the appropriate command for your compiler. For example:

```Cpp
g++ passcode_finder.cpp -o passcode_finder
```
4. Ensure the file `keylog.txt` containing the login attempts is present in the same directory.
5. Run the compiled executable.
6. The program will display the shortest passcode discovered based on the provided login attempts.
