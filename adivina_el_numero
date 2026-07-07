import random

numero_secreto = random.randint(1, 10)
intentos = 3

print("================================")
print("    BIENVENIDO AL JUEGO")
print("     ADIVINA EL NÚMERO")
print("================================")
print("Debes adivinar un número entre 1 y 10.")
print("Tienes 3 intentos.\n")

while True:
    if intentos != 0:
        print(f"Intentos restantes: {intentos}")
        opcion_usuario = int(input("Ingresa un número: "))
        if opcion_usuario < 1 or opcion_usuario > 10:
            print("El número debe estar entre 1 y 10.\n")
        elif opcion_usuario > numero_secreto:
            intentos -= 1
            print("Muy alto.")
            print(f"Te quedan {intentos} intentos.\n")
        elif opcion_usuario < numero_secreto:
            intentos -= 1
            print("Muy bajo.")
            print(f"Te quedan {intentos} intentos.\n")
        else:
            print("\n¡FELICIDADES!")
            print(f"Adivinaste el número secreto: {numero_secreto}")
            break
    else:
        print("\nGAME OVER")
        print(f"El número secreto era: {numero_secreto}")
        break
