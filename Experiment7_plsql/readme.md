![439860560-f36a0945-3d50-4478-9165-da60dbd60abe](https://github.com/user-attachments/assets/53bde98f-febf-4558-8da6-99c8f2870441)# Experiment 7: PL/SQL – Variables, Control Structures and Loops

## AIM
To write and execute simple PL/SQL programs using variables, loops, and conditional statements.


## THEORY

PL/SQL, which stands for Procedural Language extensions to the Structured Query Language (SQL). It is a combination of SQL along with the procedural features of programming languages.

**Syntax:**
```sql
DECLARE 
   <declarations section> 
BEGIN 
   <executable command(s)>
EXCEPTION 
   <exception handling> 
END;
```

### Basic Components of PL/SQL Block:
- DECLARE: Section to declare variables and constants.
- BEGIN: The execution section that contains PL/SQL statements.
- EXCEPTION: Handles errors or exceptions that occur in the program.
- END: Marks the end of the PL/SQL block.

# PL/SQL Programs – Steps and Expected Output

## 1. Write a PL/SQL program to find the Greatest of Two Numbers

### Steps:
- Declare two numeric variables and initialize them.
- Use an `IF` statement to compare the values.
- Display the greater number using `DBMS_OUTPUT.PUT_LINE`.

**Expected Output:**  
Greater number is: 80

![439859021-44fcbc07-4b38-4438-883c-4e587a2d5018](https://github.com/user-attachments/assets/f45e0f6f-6c04-44d3-bc40-143b43dd37df)


---

## 2. Write a PL/SQL program to Calculate Sum of First N Natural Numbers

### Steps:
- Declare a variable `n` and assign a value (e.g., 10).
- Initialize a `sum` variable to 0.
- Use a `WHILE` loop to iterate from 1 to `n`, adding each number to the sum.
- Display the result using `DBMS_OUTPUT.PUT_LINE`.

**Expected Output:**  
Sum of first 10 natural numbers is: 55

![439859287-4f699769-2b39-4cb4-8822-8f9de284ab3b](https://github.com/user-attachments/assets/e8dac37b-bc03-4fb0-96a6-32c12050cc60)

---

## 3. Write a PL/SQL program to generate Fibonacci series

### Steps:
- Declare the variable `n` to indicate how many terms to generate.
- Initialize the first two Fibonacci numbers (0 and 1).
- Use a loop to generate the next terms using the formula `c = a + b`.
- Print each term in the series.

**Expected Output:**  
n = 7  
Fibonacci sequence: 0, 1, 1, 2, 3, 5, 8

![439860971-79af3aa7-1ecc-4f4c-aedc-b2e5b58a1b42](https://github.com/user-attachments/assets/88642474-9043-46af-b3a0-ae45fbbacd73)

---

## 4. Write a PL/SQL Program to display the number in Reverse Order

### Steps:
- Declare a variable `n` and assign a value (e.g., 1535).
- Use a loop to extract each digit using modulo and reverse the number.
- Display the reversed number.

**Expected Output:**  
n = 1535  
Reversed number is 5351


![439859970-54784661-a9fc-4c3e-a2bc-65f48c6c6cb1](https://github.com/user-attachments/assets/43ac39e7-8764-46be-883d-feeccf19bc0b)

---

## 5. Write a PL/SQL program to find the largest of three numbers

### Steps:
- Declare three numeric variables `a`, `b`, and `c`.
- Use nested `IF-ELSIF-ELSE` conditions to find the largest among the three.
- Display the largest number.

**Expected Output:**  
a = 10, b = 9, c = 15  
Largest of three number is 15

![439860560-f36a0945-3d50-4478-9165-da60dbd60abe](https://github.com/user-attachments/assets/c8d9c3f7-0beb-4036-a980-b90ee05ddba2)



## RESULT
Thus, the PL/SQL programs using variables, conditionals, and loops were executed successfully.
