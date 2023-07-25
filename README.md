# Coffee Machine OOPS Concept Mini Project

![Coffee Machine]

## Overview

Welcome to the Coffee Machine OOPS Concept Mini Project! This project is a Python-based simulation of a coffee machine, implementing Object-Oriented Programming (OOPS) principles. The program allows users to interact with the coffee machine, make drink selections, process coins, and dispense drinks based on available resources.

## Features

1. **Prompt User for Drink Selection:**
   - The program prompts the user by asking, "What would you like? (espresso/latte/cappuccino/):"
   - Based on the user's input, the program will decide what to do next.
   - After each action (e.g., drink dispensing), the prompt shows again to serve the next customer.

2. **Turn Off the Coffee Machine:**
   - To turn off the coffee machine, the user can enter "off" as the secret word.
   - When "off" is entered, the program ends execution.

3. **Print Report:**
   - If the user enters "report" to the prompt, a report is generated, showing the current resource values.
   - The report includes the quantities of water, milk, coffee, and the amount of money in the machine.

4. **Check Resources Sufficiency:**
   - When the user chooses a drink, the program checks if there are enough resources to make that drink.
   - If any resource (e.g., water, milk, coffee) is insufficient to make the selected drink, the program prints an appropriate message (e.g., "Sorry, there is not enough water.").

5. **Process Coins:**
   - If there are sufficient resources to make the selected drink, the program prompts the user to insert coins.
   - The program accepts quarters ($0.25), dimes ($0.10), nickels ($0.05), and pennies ($0.01).
   - The monetary value of the inserted coins is calculated and displayed.

6. **Check Transaction Success:**
   - After processing the coins, the program checks if the user has inserted enough money to purchase the selected drink.
   - If the user hasn't inserted enough money, the program refunds the money with an appropriate message (e.g., "Sorry, that's not enough money. Money refunded.").
   - If the user has inserted enough money, the cost of the drink is added to the machine's profit, which is reflected in the next "report."

7. **Offer Change (if applicable):**
   - If the user has inserted too much money, the machine offers change.
   - The change is rounded to 2 decimal places and displayed as an appropriate message (e.g., "Here is $2.45 in change.").

8. **Make Coffee:**
   - If the transaction is successful and there are enough resources to make the selected drink, the ingredients are deducted from the coffee machine resources.
   - After making the drink, the program displays a message to the user (e.g., "Here is your latte. Enjoy!") if "latte" was their choice of drink.

