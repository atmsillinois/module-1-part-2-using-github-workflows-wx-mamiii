# Lunch Reminder - README - Mod 1 Part 2

This simple Python program helps you keep track of your eating schedule based on the common guideline that people should eat approximately every 4 hours. It asks you how many hours ago you last ate, then provides a friendly reminder about whether you are overdue, early, or right on time for your next meal.

## How it Works

1. The program sets a baseline of 4 hours between meals (supposed_to_eat = 4).

2. It prompts the user to enter how many hours ago they last ate (input() expects an integer).

3. Based on the input:
   > If you ate more than 4 hours ago → it tells you how many hours you are overdue.
   > 
   > If you ate less than 4 hours ago → it tells you how many hours until your next meal.
   > 
   > If you ate exactly 4 hours ago → it reminds you it’s the perfect time to eat again.

4. At the end, the program always prints a self-care reminder:
   > _Take care of yourself! :')_

This project is licensed under the terms of the MIT license.
