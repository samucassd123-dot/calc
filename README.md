with open("calculadora.py", "w") as arquivo:
    arquivo.write("""print("=== CALCULADORA ===")

while True:
    print("\\n1 - Somar")
    print("2 - Subtrair")
    print("3 - Sair")

    opcao = input("Escolha: ")

    if opcao == "3":
        break

    n1 = float(input("Primeiro número: "))
    n2 = float(input("Segundo número: "))

    if opcao == "1":
        print("Resultado:", n1 + n2)
    elif opcao == "2":
        print("Resultado:", n1 - n2)
""")