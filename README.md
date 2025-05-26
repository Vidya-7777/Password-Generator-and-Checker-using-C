# Password Generator and Checker

A C-based console application to help users generate strong passwords, check their strength, and estimate the time it would take to crack them.

---

## Overview

In the current digital age, passwords play a crucial role in protecting personal and sensitive data. However, many users often use weak or predictable passwords. This project aims to provide a simple tool to not only **generate secure passwords** but also **evaluate their strength** and **estimate their vulnerability** using C programming.

---

## About the Project

This project has three major functionalities:

1. **Password Generator**
   - Users can customize the password length and character composition (uppercase, lowercase, numbers, special characters).
   - Randomized password is generated using `rand()`.

2. **Password Strength Checker**
   - Takes user password input and checks:
     - If it includes uppercase, lowercase, digit, and special characters
     - If it avoids personal details like name, username, and DOB
     - If the password is at least 8 characters long

3. **Password Crack Time Estimator**
   - Calculates the number of possible combinations
   - Estimates cracking time based on character complexity and length

---

## Features

- Custom password generation
- Strength analysis with detailed suggestions
- Crack time estimation in milliseconds
- User-friendly command-line menu interface

---

## Tech Stack

- **Language**: C
- **Concepts Used**:
  - Strings & Arrays
  - Functions
  - Conditional Statements & Loops
  - Boolean Logic
  - Basic Combinatorics

---

## Conclusion

This project provides a comprehensive tool for password management, including generation, strength evaluation, and estimation of time required to crack a password. 
It emphasizes important security practices such as avoiding personal information, using a mix of character types, and maintaining adequate password length.

Developed in C, the project demonstrates the integration of multiple functionalities with a focus on security awareness. 
It serves as a useful utility for users aiming to enhance their password hygiene and better understand the factors that contribute to strong, secure passwords.

---
