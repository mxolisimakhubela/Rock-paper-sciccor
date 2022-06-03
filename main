import random

possible_choice = {"R": "Rock", "P": "Paper", "S": "Scissors"}

print("Welcome! Ready to play Rock, Paper, Scissors?")

while True:
    user_choice = input("Select one: R for Rock, P for Paper and S for Scissors:").capitalize()
    if user_choice not in possible_choice:
        print("Invalid Entry.")
        continue

    computer_choice = random.choice(list(possible_choice))
    print(f"Player ({possible_choice[user_choice]}) : CPU ({possible_choice[computer_choice]})")

    if user_choice == computer_choice:
        print("It is a tie! The computer and player picked the same move")
        continue

    elif user_choice == "P":
        if computer_choice == "R":
            print("Player wins!")
            exit()
        else:
            print("Computer Wins!")
            exit()

    elif user_choice == "S":
        if computer_choice == "P":
            print("Player wins!")
            exit()
        else:
            print("Computer Wins!")
            exit()

    elif user_choice == "R":
        if computer_choice == "S":
            print("Player wins!")
            exit()
        else:
            print("Computer Wins!")
            exit()
