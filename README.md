# Exceptional-Handling


##  Aim  
To understand and implement exception handling in C++ using the `try`, `throw`, and `catch` mechanism through the following programs:  
1. Division of two numbers (with division by zero check)  
2. Age validation (checking if the user is underage)  

---

##  Objectives
- Learn how C++ handles runtime errors gracefully.  
- Understand the use of `try`, `throw`, and `catch` blocks.  
- Practice throwing exceptions of different data types.  
- Explore exception handling as an alternative to traditional error handling using conditions.  
- Ensure program safety and reliability during abnormal situations.  

---

##  Theory

### What is Exception Handling?
Exception handling is a mechanism to detect and handle runtime errors in a structured way.  
Instead of terminating the program abruptly when an error occurs, exceptions allow the program to **“catch” the error and respond to it.**

### Need for Exception Handling
- Prevents program crashes from runtime errors such as division by zero, invalid input, file not found, or out-of-range access.  
- Provides a structured, safer, and cleaner way to deal with errors compared to traditional `if-else` checks.  

### Components of Exception Handling
- **`try` block** → Contains the code where an exception might occur.  
- **`throw` statement** → Used to signal that an exception has occurred.  
- **`catch` block** → Handles the exception thrown by `throw`.  

### Advantages
- Improves program reliability and security.  
- Separates error-handling code from normal program logic.  
- Handles unexpected events without crashing the program.  
- Allows multiple types of errors to be handled in one program.  

---

## Algorithms

### Division Program (Division by Zero Check)
1. Start.  
2. Input two numbers: numerator and denominator.  
3. Begin a `try` block.  
4. If denominator = 0 → `throw` an exception.  
5. Else → perform division and display the result.  
6. In the `catch` block, handle the exception by displaying **"ERROR: Division by 0"**.  
7. Stop.  

### Age Validation Program
1. Start.  
2. Input age.  
3. Begin a `try` block.  
4. If age < 18 → `throw` an exception (underage).  
5. Else → display valid age and approval message.  
6. In the `catch` block, handle the exception by displaying **"ERROR: Underage"**.  
7. Stop.  

---

##  Concepts Used
- Exception handling mechanism (`try`, `throw`, `catch`).  
- Runtime error checking (division by zero, underage validation).  
- Data-type-specific exceptions (`float` for division, `int` for age).  
- Program safety (prevents crashes).  

---

##  Conclusion
- Exception handling is a powerful tool in C++ for writing safe and reliable programs.  
- The **Division Program** demonstrates how to avoid mathematical errors like division by zero.  
- The **Age Validation Program** highlights how exceptions can be used for logical input checks.  
- By separating error-handling code from normal execution, exception handling improves program clarity and prevents crashes.  
- Particularly useful in **large applications** where multiple types of errors may occur.  

---
