# Looping-Construct-with-Floating-Point-Numbers
Floating Point Statistics is a Python program that reads five floating-point numbers from the user, calculates the total, average, maximum, minimum, and interest at 20%, and displays the results. It uses input validation, a while-loop, and formatted output.

# Screenshots
<img width="1655" alt="Screenshot 2025-04-27 at 11 19 01 PM" src="https://github.com/user-attachments/assets/13110bd9-315a-4b6d-b9ff-b3a8c889ebee" />

# Psuedocode

1. Initialize:
    - total = 0
    - count = 0
    - max = smallest possible value
    - min = largest possible value
2. WHILE count < 5:
    a. Prompt the user to enter a floating-point number
    b. Validate input (make sure it's a number)
    c. Add the number to total
    d. Update max if the number is greater than current max
    e. Update min if the number is less than current min
    f. Increment count
3. After loop ends:
    - Calculate average = total / 5
    - Calculate interest = total * 0.20
4. Display:
    - Total
    - Average
    - Maximum
    - Minimum
    - Interest at 20%
