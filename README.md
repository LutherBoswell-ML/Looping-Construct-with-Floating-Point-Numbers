# Looping-Construct-with-Floating-Point-Numbers
Floating Point Statistics is a Python program that reads five floating-point numbers from the user, calculates the total, average, maximum, minimum, and interest at 20%, and displays the results. It uses input validation, a while-loop, and formatted output.

# Screenshots
<img width="1706" alt="Screenshot 2025-04-29 at 2 19 18 PM" src="https://github.com/user-attachments/assets/372a8d1f-2131-4c58-b23f-b5ba9ae4ff22" />


# Psuedocode
Start
Set total = 0, count = 0
Set max = very small number (negative infinity)
Set min = very large number (positive infinity)

While count < 5:
    Prompt user to enter a floating-point number
    If input is valid:
        Add number to total
        Increment count
        Update max if number > max
        Update min if number < min
    Else:
        Inform user input is invalid and retry

Calculate average = total / 5
Calculate interest = total * 0.20

Print total, average, max, min, and interest
End

