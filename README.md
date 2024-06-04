# Tri-ngulos
def valorequi(a,b,c):
    if a == b == c:
        print("triângulo equilátero")
    elif a == b or a == c or b== c:
        print("triângulo isócele")
    else:
        print("triândgulo escaleno")

while True:
    a = float(input("Digite o valor :"))
    b = float(input("Digite o valor :"))
    c = float(input("Digite o valor :"))

    valorequi(a,b,c)
    continuar = input("Quer continuar (s/n): ").strip().lower()
    if continuar != "s":
        print("Encerramos o prorama")
        break

