# number-guessing-game-in-python
# here I have created number guessing game with only one chance using for loop.
# onlyh one chance to tell the right number

import random                                              # import random module so that it chooses randomly number
print("welcome to the word guessing game")                    
low_number = int(input("enter lower number"))              # here we type the lower number from where it has to be started
upper_number = int(input("enter upper number"))            # here we type upper number till where it has to be ended
random_number = random.randint(low_number, upper_number)   # here we used random.randint to shuffle number between ranges

guessing_number = int(input("guess a number"))             # here we type guessing number which number we have to be guessed
if guessing_number == random_number:                       # here we use if else statment to find the right random number
    print("guessed right")
else:
    print("guessed wrong")

