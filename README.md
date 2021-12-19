our program is numberguessing game
import random number
the numbers are between1to100
guess any number from  1to100
the numbe rare turns have used 
print("your guess was low,please enter a higher number")
print("your guess was high,please enter a lower number")




# guess the number game in python by codeSpeedy.com
import random
random_number = random.randint(1,100)
win = False
Turns =0
while win==False:
    your_guess = input("Enter a number between 1 and 100")

    Turns +=1
    if random_number==int(your_guess):
        print("you won!")
        print("Number of turns you have used: ",Turns)
        win == True
        break
    elif(random_number>int(your_guess)):

        print("your guess was low,please enter a higher number")
    else:
        print("your guess was high,please enter a lower number")

