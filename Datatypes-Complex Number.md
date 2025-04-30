# 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program

real_part = int(input("Enter the real part of the complex number: "))
imaginary_part = int(input("Enter the imaginary part of the complex number: "))

complex_num = complex(real_part, imaginary_part)

print(f"\nThe complex number is: {complex_num}")
print(f"Real part: {complex_num.real}")
print(f"Imaginary part: {complex_num.imag}")

## Output

![Screenshot 2025-04-30 054325](https://github.com/user-attachments/assets/e4539d50-b7c8-44f5-9da5-b2495710e37b)

## Result

This program is successfully executed.
