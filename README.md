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
def multiplicar(a, b):
    return a * b

def dividir(a, b):
    if b == 0:
        return "Error: No se puede dividir por cero."
    return a / b

def main():
    print("Operaciones: Multiplicación y División")
    num1 = float(input("Ingresa el primer número: "))
    num2 = float(input("Ingresa el segundo número: "))
    operacion = input("¿Qué operación deseas realizar? (multiplicar/dividir): ").strip().lower()

    if operacion == "multiplicar":
        resultado = multiplicar(num1, num2)
        print(f"El resultado de multiplicar {num1} x {num2} es: {resultado}")
    elif operacion == "dividir":
        resultado = dividir(num1, num2)
        print(f"El resultado de dividir {num1} ÷ {num2} es: {resultado}")
    else:
        print("Operación no válida.")

if __name__ == "__main__":
    main()
