# Printf

`Printf` is a project that involves implementing a custom version of the standard C library function `printf`. This project is designed to deepen your understanding of variable argument lists, format specifiers, and output formatting in C. The goal is to create a minimal yet functional `printf` implementation that supports various format specifiers and conversion types.

## Table of Contents

- [Printf](#printf)
	- [Table of Contents](#table-of-contents)
	- [About the Project](#about-the-project)
	- [Features](#features)
	- [Supported Format Specifiers](#supported-format-specifiers)
	- [Getting Started](#getting-started)
		- [Prerequisites](#prerequisites)
		- [Installation](#installation)

## About the Project

The `Printf` project involves implementing a custom version of the `printf` function, which formats and prints data to the standard output. This function should handle different data types and format specifiers, allowing for flexible and customizable output formatting.

## Features

- **Custom Implementation**: A custom implementation of the `printf` function.
- **Format Specifiers**: Support for various format specifiers to handle different data types.
- **Variable Argument Lists**: Handling of variable arguments using `stdarg.h`.
- **Output Formatting**: Ability to format and print data with specified width, precision, and alignment.

## Supported Format Specifiers

The custom `printf` implementation supports the following format specifiers:

- **`%d`** or **`%i`**: Print an integer.
- **`%u`**: Print an unsigned integer.
- **`%x`**: Print an integer in hexadecimal (lowercase).
- **`%X`**: Print an integer in hexadecimal (uppercase).
- **`%s`**: Print a string.
- **`%c`**: Print a single character.
- **`%p`**: Print a pointer address.
- **`%f`**: Print a floating-point number (may require additional implementation).

## Getting Started

### Prerequisites

- **gcc** or any C compiler that supports C99 or later.
- **Make** build tool.

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/4b93f/Printf.git
   cd Printf
