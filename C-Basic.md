# C Basics Documentation

## 1. Data Types

| Data Type | Description |
| :--- | :--- |
| `int` | Stores integer (whole number) values. |
| `float` | Stores single-precision floating-point numbers (decimals). |
| `double` | Stores double-precision floating-point numbers with higher accuracy. |
| `char` | Stores a single character/byte of data. |
| `bool` | Stores boolean values (`true` or `false`). |
| `void` | Represents an empty or non-existent data type. |

## 2. Format Specifiers

| Specifier | Description |
| :--- | :--- |
| `%d` | Signed decimal integer |
| `%u` | Unsigned decimal integer |
| `%o` | Octal representation |
| `%x` | Hexadecimal representation (lowercase) |
| `%X` | Hexadecimal representation (uppercase) |
| `%f` | Floating-point number |
| `%e` | Exponential format (scientific notation) |
| `%c` | Single character |
| `%s` | String of characters |
| `%ld` | Long signed decimal integer |

## 3. Input/Output Functions

* **`scanf()`**: Reads formatted input from standard input (keyboard).
* **`printf()`**: Displays formatted output to standard output (screen).
* **`getchar()`**: Reads a single character from standard input.
* **`putchar()`**: Writes a single character to standard output.
* **`fgets()`**: Reads a line/string from standard input safely avoiding buffer overflow.
* **`puts()`**: Writes a string to standard output followed by a newline character (`\n`).

## 4. Escape Sequences

* `\n`: Newline – moves the cursor to the beginning of the next line.
* `\t`: Horizontal Tab – inserts a tab space.
* `\\`: Backslash – displays a literal backslash character.
* `\"`: Double Quote – displays a double quotation mark inside a string.
* `\b`: Backspace – moves the cursor back one character.

## 5. Precision

Precision for floating-point values in C is specified using `.N` within format specifiers (e.g., `%.Nf`), where `N` indicates how many digits to display after the decimal point.

**Example:**
* `%.2f` prints `12.35` for `12.34567` (rounded to 2 decimal places).
* `%.4f` prints `12.3457` for `12.34567` (rounded to 4 decimal places). 
