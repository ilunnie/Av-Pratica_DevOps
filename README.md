# Avaliação Prática sobre DevOps para ETS

### Objetivos:

1. Crie uma pasta com o nome do projeto (a sua escolha) e um arquivo chamado calculadora.py

2. Adicione o seguinte conteúdo ao arquivo:

```
print('Bem vindo a calculadora Bosch')

print('\nOperações:\n1 - Soma\n2 - Subtração\n3 - Divisão\n4 - Multiplicação')

op = int(input('\nQual operação você deseja fazer? '))
valor1 = float(input('Digite o primeiro valor: '))
valor2 = float(input('Digite o segundo valor: '))
```

3. Crie um repositório público em seu GitHub



4. Abra o seu terminal de comando e adicione a origem remota e conecte seu projeto local com o GitHub



5.Verifique as alterações do seu projeto através de comando git



6. Faça um commit com uma mensagem útil e na sequência, um push para o repositório remoto



7. Crie uma nova Branch chamada "Feature"



8. Adicione o restante do algoritmo abaixo na nova branch criada:


```
if op == 1:
    print('\nR:', valor1 + valor2)

elif op == 2:
    print('\nR:', valor1 - valor2)

elif op == 3:
    print('\nR:', valor1 / valor2)

elif op == 4:
    print('\nR:', valor1 * valor2)

else:
    print('Algo deu errado')
```



9. Verifique as alterações do seu projeto e adicione novamente a um commit



10. Mescle as versões inserindo a nova Feature ao projeto principal



11. Envie para o GitHub



12. Acesse a pasta do projeto e crie um arquivo chamado minhas_senhas_secretas.txt



13. Garanta que o arquivo minhas_senhas_secretas.txt seja não rastreável



14. Adicione, commite e envie para o repositório



15. Crie uma versão "V1.0" a ser disponibilizada, do projeto criado até aqui



16. Por fim, envie para o repositório.



Obs: Tire print de todos os comandos do console