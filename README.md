import random 


caracteres = "+-/*!&$#?=@abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"

cantidad = int(input("¿cuantos caracteres tiene la contraseña?" ))

contrasena = ""

for i in range(cantidad):
    y = random.choice(caracteres)
    contrasena = contrasena + x

print(contrasena)      
