#Guess The Number

#Write a programme where the computer randomly generates a number between 0 and 20.
#The user needs to guess what the number is. 
#If the user guesses wrong, tell them their guess is either too high, or too low. 
#This will get you started with the random library if you haven't already used it.

from random import randint
x=randint(0,20)
y=int(input("Please guess the number between 0 to 20 : "))
if x==y:
    print("Your guess is correct")
elif y>x:
    print("Your guess is higher than the number")
else:
    print("Your guess is lower than the number")
print("The number is {}".format(x))
