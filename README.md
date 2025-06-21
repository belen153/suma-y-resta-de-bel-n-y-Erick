# suma-y-resta-de-bel-n-y-Erick
def sumar(a, b):
    return a + b

def restar(a, b):
    return a - b

def main():
    print("Programa para sumar y restar dos números.")
    a = float(input("Introduce el primer número: "))
    b = float(input("Introduce el segundo número: "))
    
    print(f"Suma: {a} + {b} = {sumar(a, b)}")
    print(f"Resta: {a} - {b} = {restar(a, b)}")

if __name__ == "__main__":
    main()
    def multiplicar(a, b):
    return a * b

def dividir(a, b):
    if b == 0:
        return "No se puede dividir entre cero"
    return a / b

print("Operaciones de multiplicación y división")
num1 = float(input("Ingresa el primer número: "))
num2 = float(input("Ingresa el segundo número: "))

# Multiplicación
resultado_mult = multiplicar(num1, num2)
print(f"{num1} x {num2} = {resultado_mult}")

# División
resultado_div = dividir(num1, num2)
print(f"{num1} ÷ {num2} = {resultado_div}")
