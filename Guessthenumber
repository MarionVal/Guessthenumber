import random


def adivina_el_numero(x):

    print("==========================")
    print(" !Bienvenido(a) al juego! ")
    print("==========================")

    numero_aleatorio = random.randint(1, x)

    prediccion = 0

    while prediccion != numero_aleatorio:
        # El usuario ingresa un numero 
        prediccion = input(f"Adivina un numero entre 1 y {x}: ") # f-string

        if prediccion < numero_aleatorio:
            print("Intenta otra vez.Este numero es muy pequeno. ")
        elif prediccion > numero_aleatorio:
            print("Intenta otra vez. Este numero es muy grande. ")
    
    print(f" !Felicitaciones! Adivinaste el numero {numero_aleatorio} correctamente. ")


adivina_el_numero(10)
