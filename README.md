Python-simple password generator
#简单密码生成器


# 1) Random characters & numbers
#Create a list of characters & numbers, stored in a variable called chars.
#To choose a random character, you’ll need to import the random module.
#Now you can choose a random character & number from the list, and store it in a variable called password.
import random
#Finally, you can print your (very short!) password to the screen.
import random
# 2)  A random password
#To create a password, you will add random characters to it, one at a time. To start with, your password variable should be empty. Add this line to your code:
#Use your length variable to repeat as many times as the user entered.
# 3)  Choosing a password length
#First, ask the user to input a number of password &  password length they want, and store it 
#Use int() to turn the user’s input into a whole number.
# 4)  Lots of passwords
# allow the user to enter the number of password they want 


code（编码）:


import  random
chars = 'abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ123456789'
number = input('number of passwords?')
number = int(number)
length = input('password length?')
length = int(length)

for p in range(number):
    password = ''
    for c in range(length):
        password += random.choice(chars)
    print(password)
