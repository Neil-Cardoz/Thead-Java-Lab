# Java Threading Examples

This project demonstrates basic Java threading concepts using two different approaches:
1. Extending the `Thread` class (`MyThread.java`)
2. Implementing the `Runnable` interface (`MyRunnable.java`)

## Features

- Thread creation and management
- Thread priority setting
- Fibonacci series calculation in separate threads
- Prime number checking functionality
- Thread state monitoring

## Classes

### MyThread
- Extends `Thread` class
- Creates multiple threads with different priorities
- Calculates Fibonacci series up to a specified number
- Includes prime number checking capability

### MyRunnable
- Implements `Runnable` interface
- Takes user input for Fibonacci calculation
- Demonstrates basic thread creation and execution

## Usage

To run the Thread class example:
```java
java MyThread
```

To run the Runnable interface example:
```java
java MyRunnable
```

## Sample Output

MyThread will output:
- Main thread ID
- Thread IDs, names, and priorities
- Fibonacci series calculations

MyRunnable will:
- Prompt for user input
- Calculate and display Fibonacci series
- Show thread status
