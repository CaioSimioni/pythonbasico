# Aprender Python - Básico

![Python](https://www.python.org/static/community_logos/python-logo.png)

## Índice

1. [Introdução](#introducao)
2. [Conceitos Básicos](#conceitosbasicos)
3. [Estruturas de Controle](#estruturasdecontrole)
4. [Funções](#funcoes)
5. [Manipulação de Dados](#manipulacaodedados)
6. [Outros](#formatacao)
7. [Referências](#referencias)

<div id="introducao" />

## Introdução

O Python é uma linguagem de programação de alto nível, interpretada e conhecida por sua sintaxe simples e facilidade de aprendizado. Ela é amplamente utilizada em diversos campos, como desenvolvimento web, ciência de dados, automação, inteligência artificial, entre outros. Python é uma linguagem poderosa que promove a produtividade e a legibilidade do código.

<div id="conceitosbasicos" />

## Conceitos Básicos
Aqui estão os principais pontos para começar a entender Python:

**Sintaxe Simples**: A sintaxe do Python é limpa e intuitiva. Exemplo de um programa básico que imprime uma mensagem:

```python
print("Olá, Mundo!")
```

**Variáveis e Tipos de Dados**:

- Inteiros: ` x = 10 ` <br>
- Float (ponto flutuante): `y = 3.14` <br>
- Strings: `nome = "Python"` <br>
- Booleanos: `ativo = True` <br>

**Operadores Matemáticos**:

- Soma: `2 + 2` <br>
- Subtração: `5 - 3` <br>
- Multiplicação: `4 * 3` <br>
- Divisão: `10 / 2` (retorna um número float) <br>
- Divisão inteira: `10 // 3` (retorna um número inteiro) <br>
- Exponenciação: `2 ** 3` <br>

**Entrada de Dados**:

```python
nome = input("Digite seu nome: ")
print("Olá,", nome)
```

<div id="estruturasdecontrole" />

## Estruturas de Controle

**Condicionais (if/else)**:

```python
idade = 18
if idade >= 18:
    print("Você é maior de idade.")
else:
    print("Você é menor de idade.")
```

**Laços de Repetição**:

- For Loop:

    ```python
    for i in range(5):
        print("Número:", i)
    ```

- While Loop:
    ```python
    contador = 0
    while contador < 5:
        print("Contador:", contador)
        contador += 1
    ```

<div id="funcoes" />

## Funções

As funções em Python são definidas com a palavra-chave def. Elas ajudam a organizar o código em blocos reutilizáveis.

```python
def saudacao(nome):
    print("Olá,", nome)

saudacao("Caio")
```

**Funções com Retorno**:

```python
def soma(a, b):
    return a + b

resultado = soma(3, 4)
print("Resultado:", resultado)
```

<div id="manipulacaodedados" />

## Manipulação de Dados

**Listas**:

- Criando uma lista: `frutas = ["maçã", "banana", "laranja"]` <br>
- Acessando elementos: `print(frutas[1]) # banana` <br>
- Adicionando elementos: `frutas.append("uva")` <br>
- Removendo elementos: `frutas.remove("banana")` <br>

**Dicionários**:

- Criando um dicionário:
    ```python
    aluno = {"nome": "Caio", "idade": 25, "curso": "Engenharia"}
    print(aluno["nome"])
    ```

- Adicionando uma chave-valor: `aluno["nota"] = 8.5` <br>

- Removendo uma chave: `del aluno["idade"]` <br>

**Tuplas**:

- Uma tupla é uma coleção imutável: `pontos = (10, 20, 30)` <br>

<div id="formatacao" />

## Formatação de Strings

**Concatenação**:

```python
nome = "Caio"
mensagem = "Olá, " + nome + "!"
print(mensagem)
```

**Interpolação**:

```python
nome = "Caio"
idade = 25
print(f"Meu nome é {nome} e eu tenho {idade} anos.")
```

<div id="referencias" />

## Referências

- [Documentação Oficial do Python](https://docs.python.org/3/)
- [Guia de Estilo para Python (PEP 8)](https://www.python.org/dev/peps/pep-0008/)
- [W3Schools - Python Tutorial](https://www.w3schools.com/python/)
