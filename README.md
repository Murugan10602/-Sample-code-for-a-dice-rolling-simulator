# -Sample-code-for-a-dice-rolling-simulator
# Sample code for a dice rolling simulator
import random

def roll_dice():
    return random.randint(1, 6)

while True:
    user_input = input("Roll the dice? (yes/no): ").lower()
    if user_input == "yes":
        print(f"You rolled a {roll_dice()}")
    elif user_input == "no":
        break
    else:
        print("Invalid input. Please enter 'yes' or 'no'.")
