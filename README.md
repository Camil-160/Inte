nombre = input("¿Cómo te llamas? ")
numero = int(input("Escribe un número: "))

if numero % 2 == 0:
    print(f"Hola {nombre}, el número {numero} es par.")
else:
    print(f"Hola {nombre}, el número {numero} es impar.")
