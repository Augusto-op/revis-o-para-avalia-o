nome = input("Nome do paciente: ")
peso = float(input("insira o peso:"))

altura = float(input("insira a altura:"))
resultado = (peso /altura ** 2)

if resultado < 18.5:
    print("Abaixo do peso")
elif 18.5 <= resultado < 24.9:
    print("Peso normal 1")
elif 25.0 <= resultado <29.9:
    print("Sobrepeso")
elif 30.0 <= resultado < 34.9:
    print("Obesidade Grau 1")
elif 35.0 <= resultado < 39.9:
    print("Obesidade Grau 2")
else:
    resultado = "Obesidade Grau 3 (mórbida)"
print(f"{nome}, sua classificacao é {resultado}, peso é: {peso})")
