import random

simvolica = "+-/*!&$#?=@abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"
len_password = int(input('длинна вашего пароля:'))
password = ''

for i in range(len_password):
    password += random.choice(simvolica)
print(password)
