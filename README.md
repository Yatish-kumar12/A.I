# pin
from random import *
user_pass = input('enter your pin ')
pin = ['1','2','3','4','5','6','7','8','9']
guess = ""

while(guess!=user_pass):
     guess = ""
     for letter in range(len(user_pass)):
         guess_letter = pin[randint(0,8)]
         guess = str(guess_letter)+str(guess)
         print(guess)
print('your pin is ',guess)

