## 🧠 Day 6: Conditional Statement Coding excercise part-1
➡️ **Focus:** coding assignments on  Nested conditionals, range checks, and combining multiple conditions.

---

### 🔹 Easy Level (19–28)

19. **Even and Greater Than 20**  
    Ask the user to input a number.  
    Check if the number is both **even** (divisible by 2) **and** greater than 20.  
    - If true, print: "The number is even and greater than 20."  
    - Otherwise, print: "Condition not met."

20. **Digit Length Classifier**  
    Input an integer and determine whether it is a **single-digit** (0–9), **double-digit** (10–99), or **triple-digit** (100–999).  
    - Print messages like:  
      - "Single-digit number"  
      - "Double-digit number"  
      - "Triple-digit number"  
    - If the number is outside this range, print: "Number is not in the 1–999 range."

21. **AM or PM Indicator**  
    Ask the user to enter the current hour in 24-hour format (0–23).  
    - If the hour is from 0 to 11, print "AM".  
    - If the hour is from 12 to 23, print "PM".  
    - Handle invalid inputs with: "Invalid hour entered."

22. **Ticket Entry System**  
    Ask the user if they have a ticket (enter `Y` or `N`).  
    - If `Y`, print "Entry allowed."  
    - If `N`, print "Entry denied."  
    - Handle invalid input with: "Invalid response. Enter 'Y' or 'N'."

23. **Fizz Checker**  
    Take a number as input.  
    - If it is divisible by 3, print "Fizz".  
    - Otherwise, print "Not Fizz."

24. **Buzz Checker**  
    Take a number as input.  
    - If divisible by 5, print "Buzz".  
    - Else, print "Not Buzz."

25. **FizzBuzz Checker**  
    Input a number and check:  
    - If divisible by both 3 and 5, print "FizzBuzz".  
    - If only divisible by 3, print "Fizz".  
    - If only divisible by 5, print "Buzz".  
    - Otherwise, print the number itself.

26. **Factor Check Between Two Numbers**  
    Ask the user to input two integers.  
    - Determine if **either** number is a **factor** of the other.  
    - If true, print: "One number is a factor of the other."  
    - Else, print: "No factor relationship."

27. **Ends with 7**  
    Input a number and check if it **ends in 7**.  
    - Example: `27`, `157`, etc.  
    - Use modulus or string slicing to check.  
    - Print appropriate message.

28. **Product Discount Check**  
    Ask the user to enter the product price.  
    - If the price is **more than ₹1000**, print: "Eligible for discount."  
    - Else, print: "Not eligible for discount."

---

### 🔸 Medium Level (29–35)

29. **Smallest of Three Numbers**  
    Ask the user to input three different numbers.  
    - Use nested `if` statements to determine the smallest number.  
    - Print: "The smallest number is: ___"

30. **Pass Status in Three Subjects**  
    Input marks (out of 100) for three subjects.  
    - If marks in **all three subjects are 40 or more**, print: "You passed all subjects."  
    - Else, print: "You failed in one or more subjects."

31. **Username & Password Validator**  
    Simulate a login system.  
    - Ask user to input a **username** and **password**.  
    - Check if username is `"user123"` and password is `"pass123"`.  
    - If both match, print: "Login successful."  
    - Else, print: "Login failed."

32. **Temperature Range Message**  
    Take temperature as input (in Celsius).  
    - If temperature < 10, print: "Cold weather"  
    - If temperature is between 10–25, print: "Warm weather"  
    - If temperature > 25, print: "Hot weather"

33. **Simple Calculator**  
    Ask the user for two numbers and the operation to perform (`+`, `-`, `*`, `/`).  
    - Perform the operation based on the user’s choice.  
    - Print the result.  
    - Handle division by zero with an appropriate error message.

34. **Name Starting with Vowel**  
    Ask for a user's name.  
    - Check if the name starts with a **vowel (A, E, I, O, U)**.  
    - Case-insensitive.  
    - Print: "Name starts with a vowel" or "Name does not start with a vowel."

35. **Check Lowercase Vowel and Not a Digit**  
    Input a single character.  
    - Check if the character is a lowercase vowel (`a, e, i, o, u`) and **not a digit**.  
    - Print: "Valid lowercase vowel" or "Invalid character."

---

### 🔺 Hard Level (36–38)

36. **Grade & Remark System (5 Subjects)**  
    Input marks for 5 subjects (out of 100).  
    - Calculate the **average marks**.  
    - Based on average, assign grade:
      - `>=90`: Grade A (Excellent)
      - `>=75`: Grade B (Very Good)
      - `>=60`: Grade C (Good)
      - `>=40`: Grade D (Pass)
      - `<40`: Grade F (Fail)  
    - Print grade and a short remark.

37. **String with Vowels and Consonants**  
    Ask the user to enter a string.  
    - Use conditionals to check if the string contains **at least one vowel** and **at least one consonant**.  
    - Print: "String contains both vowels and consonants."  
    - Else, print what is missing.

38. **Anagram Check Without Loops**  
    Ask the user to input two strings.  
    - Check if they are anagrams (contain same letters in any order).  
    - Use sorted comparison (`sorted(str1) == sorted(str2)`) and `if` condition.  
    - No loops allowed.  
    - Print: "The strings are anagrams." or "Not anagrams."

---
## Note:Part 2 of this assignment is in day-7,if u have time u can do  in day-6 itself