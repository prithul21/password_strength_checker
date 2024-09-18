# Password Strength Checker

## Overview

This project is a **Password Strength Checker** that evaluates the strength of a password based on several criteria, including:

- Password length (minimum 8 characters)
- Presence of lowercase letters
- Presence of uppercase letters
- Presence of numbers
- Presence of special characters

The tool provides feedback to the user on the strength of their password and suggestions for improvement if necessary.

## How it works

The script checks the password against the following conditions:

1. **Length**: The password should be at least 8 characters long.
2. **Lowercase letters**: The password should contain at least one lowercase letter.
3. **Uppercase letters**: The password should contain at least one uppercase letter.
4. **Numbers**: The password should contain at least one numeric character (0-9).
5. **Special characters**: The password should contain at least one special character (e.g., `!@#$%^&*()`).

Depending on how many criteria the password meets, the program categorizes it as either:

- **Strong**: Meets all five criteria.
- **Moderate**: Meets three or four criteria.
- **Weak**: Meets less than three criteria.

The program also provides feedback for improving the password's strength.

## How to use

1. Clone this repository to your local machine.
   
   ```bash
   git clone <repository-url>
