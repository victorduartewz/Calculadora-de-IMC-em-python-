print('Bem vindo ao nosso pequeno teste de cálculo de IMC.')
print('Aqui nesse teste você consegue descobrir seu indíce de massa corporal.')
acordo = input('Você concordaria em responder algumas perguntas (sim/não): ')
print()
if acordo == 'não':
    print('Não foi possível concluir o teste.')
elif acordo == 'sim':
    nome = input("Qual seu nome? ")
    idade = int(input("Qual sua idade? "))
    peso = float(input('Qual seu peso? '))
    altura = float(input('Qual sua altura? '))
    imc = peso / (altura **2)
    print()
    print('Parabéns {}. Você concluiu nosso teste. Obrigado por essa chance'.format(nome))
    print('Seu imc é: {:.2f}'.format(imc))
    if imc < 18.4:
        print('Situação Corpórea: Insuficiência Ponderal')
    elif imc > 18.5 and imc < 24.9:
        print('Situação Corpórea: Normal')
    elif imc > 25 and imc < 29.9:
        print('Situação Corpórea: Sobrepeso')
    elif imc > 30 and imc < 34.9:
        print('Situação Corpórea: Obesidade I')
    elif imc > 35 and imc < 39.9:
        print('Situação Corpórea: Obesidade II')
    elif imc > 40:
        print('Situação Corpórea: Obesidade III')
else:
    print('Resposta Inválida')
