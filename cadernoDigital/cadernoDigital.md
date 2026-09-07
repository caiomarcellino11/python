## Anotações de Aulas passadas

```python

preco = 50 # valor em R$
desconto = 10/100 # Desconto em %
desconto_real = preço * desconto
print(f"o valor em desconto é de R$ {preço - desconto_real}")

```
---
```python

# o cliente precisa dar o preço
# dar o desconto e fazer  o calculo

preco = int(input("qual o preço do produto? "))
desconto = int(input("qual o desconto do produto? "))
novo_preco = preco - (preco * desconto/100)
print(f"o valor com desconto do produto é de R$ {novo_preco}")

```
---

```py
#calcular quantos dias um produto duraria se a pessao usar x porções por dia
produto = int(input("quantos porções o produto tem? "))
consumo = int(input("quantas voce consumio no dia? "))
dias = produto / consumo
print(f"o produto vai durar {dias:.0f} dias!")
print(f"o produto vai durar {int(dias)} dias!")
```
---
```py
# para dirigira pessoa precisa ser igual ou maior que 18 anos de idade e carteira de motorista
idade = int(input("qual a sua idade? "))
carteira = True
verificador = idade >= 18 and carteira
print(verificador)
```
---
```py
usuario = input("digite a seu usuario: ")
senha = input("digite a sua senha: ")
login_verificador = usuario =="admin" and senha == "123admin"
print(f"login permitido: {login_verificador}")
```
---
```py
numero = int(input("digite um número de 1 a 10: "))

if numero == 10:
   print("acertou o número")
else:
  print("errou")
```
---
```py
idade = int(input("qual a sua idade "))

if idade >= 18:
  print("vc é maior de idade")

else:
  print("vc n é maior de idade")
```
---
```py
nota1 = float(input("qual foi sua 1 nota: "))
nota2 = float(input("qual foi sua 2 nota: "))
media = (nota1 + nota2)/2

if media == 7:
   print(f"sua média é {float(media)}")
   print("ficou muito na média, cuidado!!")

elif media >= 7:
  print(f"sua média é {float(media)}")
  print("passou")

else:
   print(f"sua média é {float(media)}")
   print("reprovo")
```
---
```py
usuario = input("digite seu usuário: ")
senha = input("digite seu senha: ")

if usuario == "admin" and senha == "123admin":
 print("usario e senha corretos")

else:
  print("usario ou senha estão incorretos")
```
---
```py
idade = int(input("qual sua idade: "))
autorizacao = input("tem autorização dos pais? (s/n): ")

if idade >= 18:
  print("acesso ao sistema")
elif idade >= 16 and autorizacao == "s":
  print("acesso ao sistema com autorização")
else:
  print("acesso negado")
```
---

esses exemplos foram criados por mim onde o professor foi passando os problemas e fui montando o códigos depois fui fazendo a correção acompanhada agora estou passado tudo que aprendi para o Readme para poder a fazer a documentaçao do meu estudo sendo como um caderno depois vou criar um outro readme.md para documentação mais formal do que foi aprendido na prática.

# 🐍 Python — Do Zero à Inteligência Artificial

Repositório criado para documentar minha jornada de estudos em Python, acompanhando o curso **Programação Python: Do Zero a Inteligência Artificial**.

O objetivo deste projeto é registrar meu aprendizado desde os fundamentos da linguagem até conceitos mais avançados, incluindo programação orientada a objetos, análise de dados, Machine Learning e Inteligência Artificial.

---

## 🎯 Objetivos

* Aprender Python desde os fundamentos.
* Desenvolver minha lógica de programação.
* Praticar a criação de programas e pequenos projetos.
* Aprender Programação Orientada a Objetos.
* Trabalhar com dados utilizando Python.
* Conhecer Machine Learning.
* Estudar conceitos de Inteligência Artificial.
* Criar projetos para meu portfólio no GitHub.

---

## 📚 Conteúdos estudados

### 🟢 Fundamentos

* [x] Introdução ao Python
* [x] Variáveis
* [x] Tipos de dados
* [x] Entrada e saída de dados
* [x] Operadores
* [x] Strings
* [x] Estruturas condicionais
* [x] Estrutura `for`
* [x] Estrutura `while`
* [ ] Listas
* [ ] Tuplas
* [ ] Dicionários
* [ ] Funções
* [ ] Módulos e pacotes

### 🔵 Programação Orientada a Objetos

* [ ] Classes e objetos
* [ ] Atributos e métodos
* [ ] Construtores
* [ ] Herança
* [ ] Polimorfismo
* [ ] Encapsulamento

### 🟣 Dados

* [ ] NumPy
* [ ] Pandas
* [ ] Matplotlib
* [ ] Análise de dados

### 🤖 Machine Learning

* [ ] Introdução ao Machine Learning
* [ ] Scikit-learn
* [ ] Modelos de Machine Learning
* [ ] Treinamento e avaliação de modelos

### 🧠 Inteligência Artificial

* [ ] Redes neurais
* [ ] TensorFlow
* [ ] Keras
* [ ] NLP
* [ ] Visão computacional
* [ ] Transformers
* [ ] IA generativa

---

## 💻 Ambiente de desenvolvimento

Atualmente estou utilizando:

* **Python**
* **Visual Studio Code**
* **Git**
* **GitHub**

Inicialmente utilizei o Google Colab, mas optei por continuar os estudos no Visual Studio Code para conseguir organizar melhor os códigos e a documentação do projeto.

---

## 📈 Progresso

Atualmente estou estudando as estruturas de repetição:

```python
for
while
```

O próximo objetivo é compreender bem essas estruturas antes de avançar para os próximos conteúdos.

---

## 📝 Sobre este repositório

Este repositório não tem apenas o objetivo de armazenar códigos.

Ele funciona como um registro da minha evolução durante os estudos, contendo exemplos, exercícios, anotações e projetos desenvolvidos ao longo do aprendizado.

> 🚧 Repositório em desenvolvimento. O conteúdo será atualizado conforme avanço nos estudos.

---

### For / while 

`for` --> utilizado quando sabemos a quantidade de vezes que eu preciso repetir a tarefa.
>quando eu sei a quantidade de vezes use `for`

`while` --> quando eu não sei a quantidade de vezes que preciso executar, depedendo de uma condição 
>quando eu não sei a quantidade mas depende de uma condição(reptir até chegar em tal número) use `while`








