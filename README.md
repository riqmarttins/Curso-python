📅 Semana 1 – Fundamentos do Python
🎯 Objetivo da semana:
Entender variáveis, tipos de dados e condições (if/else).
No fim, criar seu primeiro joguinho: Par ou Ímpar.
📌 Dia 1 – Variáveis e Tipos de Dados
# números
idade = 18
altura = 1.75

# texto
nome = "Riquelme"

# verdadeiro/falso
maior_idade = True

print("Nome:", nome)
print("Idade:", idade)
print("Altura:", altura)
print("É maior de idade?", maior_idade)
👉 Exercício: crie variáveis com suas informações e mostre no print.
📌 Dia 2 – Operadores
a = 10
b = 3

print(a + b)  # soma
print(a - b)  # subtração
print(a * b)  # multiplicação
print(a / b)  # divisão normal
print(a // b) # divisão inteira
print(a % b)  # resto da divisão
print(a ** b) # potência
👉 Exercício: faça contas que envolvam sua idade (ex.: idade * 12 = meses de vida).
📌 Dia 3 – Condições (if/else)
idade = 20

if idade >= 18:
    print("Você é maior de idade")
else:
    print("Você é menor de idade")
👉 Exercício: peça ao usuário para digitar a idade (input) e diga se ele pode tirar habilitação.
📌 Dia 4 – Input do Usuário
nome = input("Qual é o seu nome? ")
idade = int(input("Qual é a sua idade? "))

print(f"Olá, {nome}, você tem {idade} anos!")
👉 Exercício: faça um programa que pergunte o nome e a idade e diga em qual ano a pessoa vai fazer 100 anos.
📌 Dia 5 a 7 – Projeto da Semana 🎮
Jogo Par ou Ímpar
Regras:
O jogador escolhe um número.
O computador escolhe outro número aleatório.
A soma decide se é par ou ímpar.
import random

print("=== Jogo do Par ou Ímpar ===")

escolha = input("Você escolhe Par ou Ímpar? (p/i): ")
num_jogador = int(input("Digite um número: "))

num_pc = random.randint(0, 10)
print("Computador jogou:", num_pc)

soma = num_jogador + num_pc
print("Soma =", soma)

if soma % 2 == 0:
    resultado = "p"
else:
    resultado = "i"

if escolha == resultado:
    print("Você venceu! 🎉")
else:
    print("Você perdeu! 😢")
👉 Esse é seu primeiro joguinho completo em Python.
