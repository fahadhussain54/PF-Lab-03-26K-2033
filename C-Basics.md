# C Programming Basics

This document outlines the fundamental concepts of C programming covered in Lab 03.

---

## 1. Data Types

The table below summarizes the core C data types along with their typical size and description:

| Data Type | Size (Bytes) | Description |
| :--- | :--- | :--- |
| `int` | 2 or 4 | Stores whole numbers (integers) without decimals. |
| `float` | 4 | Stores single-precision fractional numbers (up to 6–7 decimal digits). |
| `double` | 8 | Stores double-precision fractional numbers (up to 15 decimal digits). |
| `char` | 1 | Stores a single character or ASCII value. |
| `bool` | 1 | Stores boolean values (`true` or `false`). Requires `<stdbool.h>`. |
| `void` | 0 | Represents the absence of a value or type. |

---

## 2. Format Specifiers

Format specifiers tell standard I/O functions how to format data during input and output:

| Format Specifier | Data Type / Representation |
| :--- | :--- |
| `%d` | Signed decimal integer |
| `%u` | Unsigned decimal integer |
| `%o` | Octal integer |
| `%x` | Hexadecimal integer (lowercase letters) |
| `%X` | Hexadecimal integer (uppercase letters) |
| `%f` | Floating-point number (decimal notation) |
| `%e` | Floating-point number (scientific notation, lowercase) |
| `%c` | Single character |
| `%s` | String (null-terminated array of characters) |
| `%ld` | Long signed decimal integer |

---

## 3. Input/Output Functions

C provides several built-in functions in standard library header files (`stdio.h`) for handling data input and output:

* **`scanf()`**: Reads formatted input from standard input (keyboard).
* **`printf()`**: Prints formatted output to standard output (console screen).
* **`getchar()`**: Reads a single character from standard input.
* **`putchar()`**: Writes a single character to standard output.
* **`fgets()`**: Reads a line/string from standard input up to a specified length or newline.
* **`puts()`**: Writes a string followed by a newline character to standard output.

---

## 4. Escape Sequences

Escape sequences represent non-printable or special control characters within strings:

| Escape Sequence | Description |
| :--- | :--- |
| `\n` | Newline — Moves the cursor to the beginning of the next line. |
| `\t` | Horizontal Tab — Inserts a tab space. |
| `\\` | Backslash — Displays a literal backslash character. |
| `\"` | Double Quote — Displays a literal double quotation mark. |
| `\0` | Null Character — Marks the end of a string. |

---

## 5. Precision

Precision in C is specified in `printf()` by inserting a dot (`.`) followed by an integer before the format specifier character (e.g., `%.2f`). 

### Rules and Examples
* **Floating-point rounding:** `%.2f` rounds floating-point output to **2 decimal places**.
* **Example Code:**
