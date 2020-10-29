# guessing-game

import random

while True: #continue forever....
 name = input("enter your name: ")
 print(f"Hello, {name} Welcome to guess the number")
 break
number = random.randint(1,150)

number =int(input("pick a number):"))
if number > 140:
    print(f"your number is too high!")

elif number < 20:
    print(f"your guess is too low!")
    
  
elif number==80:
    print(f"congratulations! you guess the number")
