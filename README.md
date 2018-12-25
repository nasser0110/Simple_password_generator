# Simple_password_generator
Python-simple password generator



# 1) Random characters & numbers

# Create a list of characters & numbers, stored in a variable called chars.

chars = 'abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ123456789'

# To choose a random character, you’ll need to import the random module.

import random

chars = 'abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ123456789'

# Now you can choose a random character & number from the list, and store it in a variable called password.
import random

chars = 'abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ123456789'

password += random.choice(chars)

# Finally, you can print your (very short!) password to the screen.
import random

chars = 'abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ123456789'

password += random.choice(chars)

print(password)

# 2)  A random password

# To create a password, you will add random characters to it, one at a time. To start with, your password variable should be empty. Add this line to your code:
import random

chars = 'abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ123456789'

password = ''

password += random.choice(chars)

print(password)

# Use your length variable to repeat as many times as the user entered.
for c in range(length):

# 3)  Choosing a password length
length = int(length)

# First, ask the user to input a password length, and store it in a variable called length
length = input('password length?')
