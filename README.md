# Calculo de Média
***
## Média de duas notas usando a linguagem de Python / Vscode.
***
Para rodar o código de calculo da média das duas notas é nescessário, paixar o sistema python, ou um compilador online.
***

Projeto Exemplo: Calculadora de Média do Aluno
def calcular_media(nota1, nota2):
    return (nota1 + nota2)  / 2
```
print("=== Sistema de Notas do Aluno ===")
n1 = float(input("Digite a primeira nota: " ))
n2 = float(input("Digite a segunda nota:"))
media = calcular_media(n1, n2)                
print(f"A média final é: {media:.2f}")

if media >= 7.0:
    print ("Status: APROVADO!")
    
else: 
     print ("Status: REPROVADO!")

Exemplos de saída:

=== Sistema de Notas do Aluno ===
Digite a primeira nota: 5
Digite a segunda nota:6
A média final é: 5.50
Status: REPROVADO!

=== Sistema de Notas do Aluno ===
Digite a primeira nota: 10
Digite a segunda nota:6
A média final é: 8.00
Status: APROVADO!

```
***
