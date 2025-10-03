# Aim: To study and implement exception handling in C++

## Theory:

In programming, dividing a number by zero is undefined and causes a runtime error. 

**Exception handling** is a mechanism to handle such errors during program execution without abruptly terminating the program. 

In C++, try block contains the code that may throw an exception. If an exception occurs, the control passes to the catch block, where the error is handled. 
In this program, if the denominator (n2) is zero, an exception is thrown. The catch block catches this exception and prints an appropriate error message, preventing the program from crashing.

Age verification is a common validation step where the system checks if a person meets a minimum age requirement (e.g., 18 years). 
In C++, exceptions provide a way to handle errors or unexpected conditions gracefully. Here, the program throws an integer exception if the age is less than 18, indicating that the user is underage.
The thrown exception is caught in the catch block where an appropriate error message is displayed. If the age is valid (18 or more), the program outputs an approval message.

## 1. Algorithm: Division by zero

**Step 1**: Start.

**Step 2**: Prompt the user to enter two floating-point numbers, n1 and n2.

**Step 3**: Read the input values.

**Step 4**: Use a try block:

- Check if n2 is zero.

- If yes, throw n2 as an exception.

- Else, perform division n1/n2 and store in ans.

**Step 5**: Display the result.

**Step 6**: Use a catch block to catch the exception of type float:

**Step 7**: Display error message indicating division by zero.

**Step 8**: End.

## 2. Algorithm: Age exception

**Step 1**: Start.

**Step 2**: Prompt the user to enter the age.

**Step 3**: Read the input value into n1.

**Step 4**: Use a try block:

- If n1 < 18, throw n1 as an exception.

- Else, print the age and approval message.

**Step 5**: Use a catch block to catch the exception of type int:

**Step 6**: Print the error message indicating underage with the thrown value.

**Step 7**: End.

## Conclusion

In this experiment we learnt that exception handling in C++ allows a program to handle runtime errors gracefully without abnormal termination. We handled situations like division by zero and invalid age input.
This ensures that instead of crashing, the program gives a meaningful error message and continues execution safely. Exception handling thus improves the reliability, robustness, and user-friendliness of C++ programs.
