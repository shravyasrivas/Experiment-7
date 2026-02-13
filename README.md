# Experiment 7: 

---

### Aim: Study of Loops and  Break Statements in Python

---

### Algorithms

#### Algorithm for Problem Statement 1: Print Numbers from 1 to 5

Step 1: Start.

Step 2: Initialize variable `i = 1`.

Step 3: Check condition `i <= 5`.

Step 4: If true, print `i`.

Step 5: Increment `i` by 1.

Step 6: Repeat Steps 3–5 until condition becomes false.

Step 7: Stop.

---

#### Algorithm for Problem Statement 2: Print Numbers from 1 to n

Step 1: Start.

Step 2: Accept an integer `n` from the user.

Step 3: Initialize `i = 1`.

Step 4: Check condition `i <= n`.

Step 5: If true, print `i`.

Step 6: Increment `i` by 1.

Step 7: Repeat until condition becomes false.

Step 8: Stop.

---

#### Algorithm for Problem Statement 3: Find Factorial of a Number

Step 1: Start.

Step 2: Accept an integer `n` from the user.

Step 3: Initialize `fact = 1`.

Step 4: While `n > 0`, multiply `fact = fact × n`.

Step 5: Decrement `n` by 1.

Step 6: Repeat until `n` becomes 0.

Step 7: Display factorial.

Step 8: Stop.

---

#### Algorithm for Problem Statement 4: Generate Fibonacci Series (n Terms)

Step 1: Start.

Step 2: Accept number of terms `n`.

Step 3: Initialize `a = 0`, `b = 1`, `i = 1`.

Step 4: While `i <= n`, print `a`.

Step 5: Compute next term `c = a + b`.

Step 6: Update `a = b`, `b = c`.

Step 7: Increment `i`.

Step 8: Repeat until condition fails.

Step 9: Stop.

---

#### Algorithm for Problem Statement 5: Fibonacci Series up to a Limit

Step 1: Start.

Step 2: Accept limit value from user.

Step 3: Initialize `a = 0`, `b = 1`.

Step 4: While `a <= limit`, print `a`.

Step 5: Update values using `a, b = b, a + b`.

Step 6: Repeat until `a` exceeds limit.

Step 7: Stop.

---

#### Algorithm for Problem Statement 6: Reverse a Number

Step 1: Start.

Step 2: Accept a number from the user.

Step 3: Initialize `rev = 0`.

Step 4: While number > 0:

  a) Extract last digit using `% 10`.
  
  b) Update `rev = rev × 10 + digit`.
  
  c) Remove last digit using `// 10`.
  
Step 5: Display reversed number.

Step 6: Stop.

---

#### Algorithm for Problem Statement 7: Check Palindrome Number

Step 1: Start.

Step 2: Accept number from user.

Step 3: Store original number in a temporary variable.

Step 4: Reverse the number using while loop.(  rev =rev * 10 + num % 10)

Step 5: Compare reversed number with original number.

Step 6: If equal, print **"Palindrome"**.

Step 7: Otherwise, print **"Not a Palindrome"**.

Step 8: Stop.

---

#### Algorithm for Problem Statement 8: Check Palindrome String Using While Loop

Step 1: Start.

Step 2: Accept string from user.

Step 3: Initialize two pointers `i = 0` and `j = length - 1`, usimg len function.

Step 4: While `i < j`, compare characters at position `i` and `j`.

Step 5: If mismatch occurs, mark as not palindrome.

Step 6: Increment `i` and decrement `j`.

Step 7: After loop, display result.
Step 8: Stop.


---

#### Algorithm for Problem Statement 9: Check Palindrome String Without Loop

Step 1: Start.

Step 2: Accept string from user.

Step 3: Reverse string using slicing `[::-1]`.

Step 4: Compare original and reversed string.

Step 5: If equal, print **"Palindrome"**.

Step 6: Otherwise, print **"Not palindrome"**.

Step 7: Stop.

---

#### Algorithm for Problem Statement 10: Count Digits in a Number

Step 1: Start.

Step 2: Accept number from user.

Step 3: Initialize `count = 0`.

Step 4: While number > 0:

  a) Increment count.
  
  b) Remove last digit using `// 10`.
  
Step 5: Display digit count.

Step 6: Stop.

---

#### Algorithm for Problem Statement 11: Exit Loop Using Break

Step 1: Start.

Step 2: Initialize `i = 1`.

Step 3: While `i < 6`, print `i`.

Step 4: If `i == 3`, terminate loop using `break`.

Step 5: Increment `i`.

Step 6: Stop.

---

#### Algorithm for Problem Statement 12: Search Element in a List

Step 1: Start.

Step 2: Define a list of numbers.

Step 3: Accept element to search from user.

Step 4: Initialize index `i = 0`.

Step 5: While `i < length of list`:

  a) Compare list element with key.
  
  b) If found, print index and exit loop using `break`.
  
  c) Increment `i`.
  
Step 6: If loop ends without break, print **"Element not found"**.

Step 7: Stop.

---

#### Algorithm for Problem Statement 13: Print Odd Numbers from 1 to 10

Step 1: Start.

Step 2: Initialize `i = 0`.

Step 3: While `i < 10`, increment `i`.

Step 4: If `i` is even (`i % 2 == 0`), skip using `continue`.

Step 5: Otherwise, print `i`.

Step 6: Repeat until condition fails.

Step 7: Stop.

---

### Theory

The **while loop** in Python is an iterative control structure that repeatedly executes a block of code as long as a given condition remains true. It is particularly useful when the number of iterations is not fixed and depends on dynamic conditions , with break statement we can stop the loop even if the while condition is true.

In this experiment, different programs were implemented using while loops to perform operations such as factorial calculation, Fibonacci series generation, palindrome checking, digit counting, list searching, and loop control using `break` and `continue`.

---

### Functions and Logic Used

#### Functions Used

• `input()` – Accepts input from the user.

• `print()` – Displays output.

• String slicing `[::-1]` – Used to reverse strings.

• `len()` – Used to find length of string/list.

---

#### Logic and Operators Used

• While Loop – Repeats execution based on condition.

• Arithmetic Operators (+, -, *, //, %) – Used for calculations.

• Relational Operators (>, <, ==, <=) – Used for condition checking.

• Modulus Operator (%) – Used for digit extraction and even/odd checking.

• Break Statement – Terminates loop immediately.

• Continue Statement – Skips current iteration.

---

### Conclusion

Through this experiment, the working and importance of the **while loop** in Python were successfully studied. The programs demonstrated how iteration helps in solving repetitive and real-world computational problems efficiently. The use of loop control statements like `break` and `continue` enhances flexibility and control in programming logic.
