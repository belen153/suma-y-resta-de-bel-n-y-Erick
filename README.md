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
