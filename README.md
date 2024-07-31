# Exp-2
# C++ Data Types and Their Sizes

This document provides information about the sizes of common data types in C++. The sizes of data types can vary depending on the system and compiler, but the following are typical sizes for most platforms.

## Common Data Types and Their Sizes

### Integer Types

- **`char`**: 
  - Size: 1 byte (8 bits)
  - Represents: Character data or small integers

- **`short`**:
  - Size: 2 bytes (16 bits)
  - Represents: Small integers

- **`int`**:
  - Size: 4 bytes (32 bits)
  - Represents: Standard integer type

- **`long`**:
  - Size: 4 bytes (32 bits) or 8 bytes (64 bits) depending on the system
  - Represents: Larger integers

- **`long long`**:
  - Size: 8 bytes (64 bits)
  - Represents: Very large integers

### Floating-Point Types

- **`float`**:
  - Size: 4 bytes (32 bits)
  - Represents: Single-precision floating-point numbers

- **`double`**:
  - Size: 8 bytes (64 bits)
  - Represents: Double-precision floating-point numbers

- **`long double`**:
  - Size: 8 bytes (64 bits) or 16 bytes (128 bits) depending on the system
  - Represents: Extended-precision floating-point numbers

### Boolean Type

- **`bool`**:
  - Size: 1 byte (8 bits)
  - Represents: Boolean values (`true` or `false`)

### Character Type

- **`wchar_t`**:
  - Size: 2 bytes (16 bits) or 4 bytes (32 bits) depending on the system
  - Represents: Wide characters for internationalization

## Checking Sizes in Your System

To check the sizes of data types on your specific system, you can use the `sizeof` operator in C++. Here’s an example program that prints the sizes of various data types:

```cpp
//saanvi
//23070123110
#include <iostream>
using namespace std;

int main() {
    cout << "Size of char: " << sizeof(char) << " byte(s)" << endl;
    cout << "Size of short: " << sizeof(short) << " byte(s)" << endl;
    cout << "Size of int: " << sizeof(int) << " byte(s)" << endl;
    cout << "Size of long: " << sizeof(long) << " byte(s)" << endl;
    cout << "Size of long long: " << sizeof(long long) << " byte(s)" << endl;
    cout << "Size of float: " << sizeof(float) << " byte(s)" << endl;
    cout << "Size of double: " << sizeof(double) << " byte(s)" << endl;
    cout << "Size of long double: " << sizeof(long double) << " byte(s)" << endl;
    cout << "Size of bool: " << sizeof(bool) << " byte(s)" << endl;
    cout << "Size of wchar_t: " << sizeof(wchar_t) << " byte(s)" << endl;

    return 0;
}
