# Random-password-generator
# a simple clean code password generator 
import random   

chars = "abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"

while 1:
    password_len = 12
    password_count = int(input("posa password thes? "))
    for Q in range (0,password_count):
        password = ''
        for Q in range(0,password_len):
            password_char = random.choice(chars)
            password        = password +password_char
        print ('to password sou einai: ',password)
