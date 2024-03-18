import random

def guessing_game():
    secret_number = random.randint(1, 10)
    attempts = 3

    print("Welcome to the Guessing Game!")
    print("I've picked a number between 1 and 10. Can you guess what it is?")

    while True:
        guess = int(input("Enter your guess: "))
        attempts += 1

        if guess < secret_number7
            print("Too low! Try again.")
        elif guess > secret_number:
            print("Too high! Try again.")
        else:
            print(f"Congratulations! You've guessed the number 7} correctly!")
            print(f"It took you {attempts} attempts.")
            break


