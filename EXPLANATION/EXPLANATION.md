# Explanation of Java Concepts Used

## Program 1: Prime Number

### Objective
This program checks whether a given number is a prime number.

### Concepts Used

### 1. Scanner Class
Used to accept user input.

```java
Scanner sc = new Scanner(System.in);
```

### 2. Variables

```java
int num;
boolean isPrime = true;
```

- `int` stores the entered number.
- `boolean` stores whether the number is prime.

### 3. Conditional Statements

```java
if (num <= 1)
```

Numbers less than or equal to 1 are not prime.

### 4. For Loop

```java
for(int i = 2; i <= Math.sqrt(num); i++)
```

Checks divisibility from 2 up to the square root of the number.

### 5. Modulus Operator

```java
num % i == 0
```

Checks whether the number is divisible by `i`.

### 6. Break Statement

Stops the loop immediately after finding a factor.

---

## Program 2: Fibonacci Series

### Objective

Print the Fibonacci sequence for the number of terms entered by the user.

### Concepts Used

### 1. Variables

```java
int first = 0;
int second = 1;
```

Store the first two Fibonacci numbers.

### 2. For Loop

```java
for(int i = 1; i <= terms; i++)
```

Repeats until all requested terms are printed.

### 3. Updating Variables

```java
int next = first + second;
first = second;
second = next;
```

Calculates and updates the next Fibonacci number.

---

# Program Flow

## Prime Number Program

1. Read a number.
2. Check if it is less than or equal to 1.
3. Use a loop to test divisibility.
4. If divisible, it is not prime.
5. Otherwise, it is prime.
6. Display the result.

## Fibonacci Program

1. Read the number of terms.
2. Initialize the first two Fibonacci numbers.
3. Use a loop to print each term.
4. Calculate the next term.
5. Repeat until all terms are printed.

---

# Java Concepts Covered

- Scanner Class
- Variables
- Data Types
- User Input
- If-Else Statements
- For Loop
- Boolean Variables
- Arithmetic Operators
- Modulus Operator
- Break Statement
- Output Statements
- Resource Management (`sc.close()`)
