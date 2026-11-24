# Student Marks and Grade Calculator

## 1. Aim
To write a Python program to calculate a student's grade based on the marks entered by the user using if, elif, and else conditional statements.

## 2. Procedure
1. Start the Python program.
2. Get the student's marks as input from the user.
3. Check whether the marks are greater than or equal to 90.
4. If true, display Grade A+.
5. Otherwise, check the remaining conditions using elif statements.
6. Assign grades according to the marks:
   - 90–100: A+
   - 80–89: A
   - 70–79: B
   - 60–69: C
   - 50–59: D
   - 35–49: E
   - Below 35: Fail
7. Display the corresponding grade and message.
8. Stop the program.

## 3. Flowchart

```text
          ┌───────────────┐
          │     START     │
          └───────┬───────┘
                  │
          ┌───────▼───────┐
          │  Enter Marks  │
          └───────┬───────┘
                  │
          ◇ Marks >= 90? ◇
             /       \
           Yes        No
            │          │
      ┌─────▼────┐  ◇ Marks >= 80? ◇
      │ Grade A+ │     /       \
      └─────┬────┘   Yes        No
            │         │          │
            │    ┌────▼───┐  ◇ Marks >= 70? ◇
            │    │Grade A │     /       \
            │    └────┬───┘   Yes        No
            │         │        │          │
            │         │   ┌────▼───┐  ◇ Marks >= 60? ◇
            │         │   │Grade B │     /       \
            │         │   └────┬───┘   Yes        No
            │         │        │        │          │
            │         │        │   ┌────▼───┐  ◇ Marks >= 50? ◇
            │         │        │   │Grade C │     /       \
            │         │        │   └────┬───┘   Yes        No
            │         │        │        │        │          │
            │         │        │        │   ┌────▼───┐  ◇ Marks >= 35? ◇
            │         │        │        │   │Grade D │     /       \
            │         │        │        │   └────┬───┘   Yes        No
            │         │        │        │        │        │          │
            │         │        │        │        │   ┌────▼───┐ ┌────▼───┐
            │         │        │        │        │   │Grade E │ │  FAIL  │
            │         │        │        │        │   └────┬───┘ └────┬───┘
            └─────────┴────────┴────────┴────────┴────────┴──────────┘
                                      │
                               ┌──────▼──────┐
                               │    STOP     │
                               └─────────────┘
```

## 4. Expected Output

The program should accept marks from the user and display the corresponding grade based on the given conditions.

Example:

```text
Nee marks enter cheyyi bro (0-100): 95
Grade: A+ | Mass bro, Topper!
```

## 5. Actual Output

```text
Nee marks enter cheyyi bro (0-100): 85
Grade: A | Super bro!
```

## Conclusion
The program successfully calculates and displays the student's grade based on the marks entered by the user using conditional statements in Python.