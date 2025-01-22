def calculadora():
    print("Bem-vindo à Calculadora!")
    print("Escolha uma operação:")
    print("1. Adição")
    print("2. Subtração")
    print("3. Multiplicação")
    print("4. Divisão")

    operacao = input("Digite o número da operação (1/2/3/4): ")

    num1 = int(float(input("Digite o primeiro número: ")))
    num2 = int(float(input("Digite o segundo número: ")))

    if operacao == '1':
        resultado = num1 + num2
        print(f"O resultado da adição é: {resultado}")
    elif operacao == '2':
        resultado = num1 - num2
        print(f"O resultado da subtração é: {resultado}")
    elif operacao == '3':
        resultado = num1 * num2
        print(f"O resultado da multiplicação é: {resultado}")
    elif operacao == '4':
        if num2 != 0:
            resultado = num1 / num2
            print(f"O resultado da divisão é: {resultado}")
        else:
            print("Erro: Divisão por zero não é permitida.")
    else:
        print("Operação inválida. Por favor, escolha uma operação válida.")


if __name__ == "__main__":
    calculadora()
    
