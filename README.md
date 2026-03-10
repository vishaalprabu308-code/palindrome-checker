# Palindrome Checker Management System

## Overview
A Java application that checks whether a given string is a palindrome. The application provides a simple and efficient way to validate if text reads the same forwards and backwards.

**Version:** 1.0

## Features
- **Palindrome Validation**: Core functionality to check if a string is a palindrome
- **Welcome Message**: Application displays name and version information on startup
- **Hardcoded Example**: Demonstrates palindrome checking with the word "madam"
- **Clean Architecture**: Well-structured code with separate methods for clarity

## How It Works
The application uses a two-pointer approach to verify if a string is a palindrome:
1. Compare the first character with the last character
2. Compare the second character with the second-to-last character
3. Continue until the middle of the string is reached
4. Return `true` if all characters match, `false` otherwise

## Requirements
- Java 8 or higher
- No external dependencies

## Compilation and Execution

### Compile
```bash
javac PalindromeCheckerApp.java
```

### Run
```bash
java PalindromeCheckerApp
```

## Output Example
```
Welcome to the Palindrome Checker Management System
Version : 1.0
Input text: madam
Is it a palindrome? : true
System initialized successfully.
```

## Future Enhancements
- User input for custom string checking
- Case-insensitive palindrome checking
- Handling spaces and special characters
- Interactive menu system
- Performance metrics for large strings


## E.Rohit- RA2411030010127