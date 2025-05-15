# 🧠 Day 7: Loop Mastery in Python

➡️ **Focus:** Understanding `while` loops, `for` loops, nested loops, and loop control statements like `break`, `continue`, and `pass`. Also covers Python's take on the missing `do-while` loop and an intro to built-in functions.

---

## 📺 Video Resources

1. 🔁 **Intro to While Loop in Python**  
   [Watch on YouTube](https://youtu.be/od9epagFFYY?si=yGM6Xd9_QxTmaAVW)

2. 🚫 **Why Python Doesn’t Have a Do-While Loop**  
   [Watch on YouTube](https://youtu.be/D-ZSTjn_TrM?si=mV5iMHC62qW9FKGe)

3. 🔂 **For Loop in Python**  
   [Watch on YouTube](https://youtu.be/mMCelsWjfac?si=sasPWrIhqutSl21B)

4. 🔁 **Nested Loop in Python**  
   [Watch on YouTube](https://youtu.be/QU3zhcSBWKU?si=H9FZVS66yNlNYRwf)

5. 🛑 **Break, Pass, and Continue Statements**  
   [Watch on YouTube](https://youtu.be/lgs_o6mDzdU?si=zOALvBjO2ezcc-Sb)

6. 🛠️ **Built-in Functions in Python**  
   [Watch on YouTube](https://youtu.be/hCMnJT14XTw?si=C206Z5w5hRaRFa4z)

---
## 📚 Blogs & Reading Material
loops in py:https://www.simplilearn.com/tutorials/python-tutorial/python-loops

## 🧠 Coding excercise:Day 6 assignments part-2 
➡️ **Focus:** Multi-condition decisions, real-life simulations, and practical applications.

---

### 🔹 Easy Level (39–48)

39. **Gender-Based Welcome**  
    Ask the user to input their gender (`M` for Male, `F` for Female, `O` for Other).  
    - Print: "Welcome Sir!" for `M`, "Welcome Ma'am!" for `F`, and "Welcome!" for `O`.  
    - Handle invalid input.

40. **Custom Greeting for 'A' Name**  
    Ask the user to input their name.  
    - If the name starts with the letter **‘A’ or ‘a’**, print: "Hello, [name]! You have a special name!"  
    - Else, print a normal greeting like: "Hello, [name]!"

41. **ID and Age Check for Access**  
    Ask:
    - Do you have an ID card? (`Y/N`)
    - Enter your age  
    - Allow access **only if ID is 'Y' and age ≥ 18**  
    - Else, deny with appropriate message

42. **Day Type Identifier**  
    Ask for a number between 1 and 7 (representing days of the week).  
    - 1 = Monday, 7 = Sunday  
    - Print "Weekday" for 1–5, "Weekend" for 6–7  
    - Handle invalid inputs

43. **Student Discount Eligibility**  
    Ask the user’s age.  
    - If age is **less than 18**, print: "Eligible for student discount."  
    - Else, print: "Not eligible for student discount."

44. **Triangle Angle Checker**  
    Input three angles.  
    - If the sum of angles equals 180 and each angle is > 0, it’s a **valid triangle**  
    - Else, print: "Invalid triangle."

45. **Century Year Checker**  
    Ask the user to enter a year.  
    - If the year ends with `00`, print: "Century year."  
    - Else, print: "Not a century year."

46. **Login Access Levels**  
    Ask the user to input their login role (`admin`, `guest`, or `user`).  
    - Print respective access message:  
      - Admin: "Full access granted."  
      - Guest: "Limited access."  
      - User: "Standard access."  
    - Handle any unrecognized input.

47. **Speeding Fine Simulation**  
    Ask the user for their speed (in km/h).  
    - Speed limit = 60 km/h  
    - If speed > 60, print: "Speeding fine applicable."  
    - Else, print: "You’re within the speed limit."

48. **Palindrome Number Checker**  
    Ask for a number and check if it’s a palindrome (same forward and backward).  
    - Example: 121 → Palindrome  
    - Use string reversal or math  
    - Print appropriate result

---

### 🔸 Medium Level (49–55)

49. **ATM PIN Check**  
    Simulate an ATM PIN system.  
    - Ask for PIN and balance  
    - Only allow transaction if:
      - PIN matches a preset value (e.g., `1234`)
      - Balance is greater than or equal to withdrawal amount  
    - Print success or failure message accordingly

50. **Bonus Eligibility**  
    Input:
    - Salary
    - Years of service  
    - If service is ≥ 5 years and salary < ₹50,000 → give a bonus of ₹5,000  
    - Print new salary or “No bonus” if not eligible

51. **Travel Fare Calculator**  
    Input:
    - Base fare (e.g., ₹50)
    - Distance in km
    - Vehicle type (`bike`, `car`, `bus`)  
    - Apply multiplier:
      - bike × 1  
      - car × 2  
      - bus × 1.5  
    - Final fare = base fare + (distance × multiplier)  
    - Print the total fare

52. **Valid Rectangle Checker**  
    Ask for the lengths of two sides (length and breadth).  
    - If both values > 0, it’s a valid rectangle  
    - Else, print: "Invalid rectangle dimensions."

53. **Equality Among Four Numbers**  
    Input 4 numbers.  
    - If **all** are equal, print: "All numbers are equal."  
    - Else, print: "Numbers are not all equal."

54. **BMI Category Checker**  
    Ask for:
    - Weight in kg
    - Height in meters  
    - Calculate BMI = weight / height²  
    - Print category:
      - <18.5: Underweight
      - 18.5–24.9: Normal
      - 25–29.9: Overweight
      - 30+: Obese

55. **Coin Breakdown (Change Return)**  
    Input an amount (e.g., ₹370)  
    - Use conditional logic to break it into:
      - ₹100 notes
      - ₹50 notes
      - ₹10 coins  
    - Don’t use loops  
    - Print number of each denomination used

---

### 🔺 Hard Level (56–62)

56. **Login System with 3 Attempts**  
    Simulate a login where:
    - User has **3 chances** to enter correct password  
    - If failed in all attempts, print: "Account blocked."  
    - If successful, print: "Login successful."

57. **Rock-Paper-Scissors Game**  
    Ask both players to enter one of: `rock`, `paper`, `scissors`  
    - Use nested conditionals to determine the winner  
    - Print: "Player 1 wins", "Player 2 wins", or "It's a tie!"

58. **Income Tax Simulator**  
    Ask:
    - Annual salary
    - Marital status (`married` or `single`)  
    - Tax rates:
      - If single and salary > ₹5,00,000 → 20%
      - If married and salary > ₹7,00,000 → 15%  
    - Else → no tax  
    - Print tax amount or "No tax applicable"

59. **Right-Angled Triangle Check**  
    Input three sides of a triangle.  
    - Check if Pythagorean Theorem holds:  
      a² + b² = c² (where c is the largest side)  
    - If yes, print: "Right-angled triangle."  
    - Else, print: "Not a right-angled triangle."

60. **Advanced Grading System with Feedback**  
    Input total marks and calculate percentage.  
    - Assign grade based on %:
      - 90–100: A+ ("Outstanding")
      - 80–89: A ("Excellent")
      - 70–79: B ("Very Good")
      - 60–69: C ("Good")
      - 50–59: D ("Average")
      - Below 50: F ("Needs Improvement")  
    - Print grade + message

61. **Mini Weather Forecast Bot**  
    Input:
    - Temperature (°C)
    - Humidity (%)
    - Wind speed (km/h)  
    - Based on conditions:
      - High temp + high humidity → “Very humid and hot”
      - Low temp + high wind → “Chilly and breezy”
      - Moderate values → “Pleasant weather”  
    - Print forecast message

62. **Manual Condition Evaluation**  
    Ask:
    - Two numbers
    - A condition symbol (`>`, `<`, `==`, `!=`, `>=`, `<=`)  
    - Manually use `if-else` to compare  
    - Print: “Condition is True” or “Condition is False”

---
