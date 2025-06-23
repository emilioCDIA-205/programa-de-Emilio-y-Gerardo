# programa-de-Emilio-y-Gerardo
def sumar(a, b):
    return a + b

def restar(a, b):
    return a - b

def main():
    print("Programa que suma y resta dos números")
    num1 = float(input("Ingresa el primer número: "))
    num2 = float(input("Ingresa el segundo número: "))

    suma = sumar(num1, num2)
    resta = restar(num1, num2)

    print(f"La suma de {num1} y {num2} es: {suma}")
    print(f"La resta de {num1} y {num2} es: {resta}")

if __name__ == "__main__":
    main()
