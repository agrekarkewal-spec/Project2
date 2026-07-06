\# Big Integer Arithmetic Library in C



A lightweight and efficient arbitrary-precision integer (BigInt) library written entirely in C. This project implements large integer arithmetic without relying on external libraries, allowing computations on integers far larger than the built-in C data types.



The library represents large integers as arrays of fixed-size words and provides a comprehensive set of arithmetic, bitwise, and utility operations. It supports configurable word sizes (8, 16, 32, or 64 bits) and uses optimized algorithms such as Karatsuba multiplication for improved performance on large operands.



\## Features



\* Arbitrary-precision integer representation

\* Configurable word sizes (8, 16, 32, or 64 bits)

\* Addition and subtraction with carry/borrow propagation

\* Multiplication using:



&#x20; \* Schoolbook multiplication

&#x20; \* Karatsuba multiplication (divide-and-conquer)

\* Binary long division

\* Modulus and DivMod operations

\* Exponentiation

\* Integer square root

\* Left and right bit shifting

\* Bitwise AND, OR, and XOR

\* Comparison and zero checking

\* Conversion between integers, decimal strings, and hexadecimal strings



\## Implementation Highlights



\* Stores integers as arrays of fixed-size words (little-endian representation)

\* Handles arbitrary-length integers limited only by the allocated array size

\* Efficient carry and borrow management across multiple words

\* Recursive Karatsuba multiplication for faster large-number multiplication

\* Clean modular implementation with separate helper and utility functions



\## Applications



\* Cryptography

\* Large integer computations

\* Number theory algorithms

\* Educational purposes for understanding arbitrary-precision arithmetic

\* Competitive programming and systems programming projects



\## Technologies Used



\* C

\* Pointer arithmetic

\* Bitwise operations

\* Dynamic stack allocation (`alloca`)

\* Divide-and-conquer algorithms

\* Manual memory management



This project demonstrates the implementation of arbitrary-precision arithmetic from first principles, covering both fundamental algorithms (addition, subtraction, multiplication, division) and advanced optimization techniques such as Karatsuba multiplication.



