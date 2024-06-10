## PYTHON

```python
print("Hello World")
```
#- Comentário

"""
Comentário
de
várias
linhas
"""

## TIPOS DE DADOS
```python
myNum = 9

myFloatNum = 8.99

myLetter = 'A'

myBool = False

myText = "Hello World"
```
## OPERADORES
```python
x = 5
y = 3

result = x * y  # result será 15

result = x / y  # result será 1

z = 5
z += 1  # z será 6

a = 10
a += 5  # a será 15
```
## STRINGS
```python

txt = "Hello"
txt_length = len(txt)  # Retorna o comprimento da string (5)

upper_txt = txt.upper()  # Retorna "HELLO"

lower_txt = txt.lower()  # Retorna "hello"

txt1 = "Hello"
txt2 = " World"
concat_txt = txt1 + txt2  # Retorna "Hello World"

concat_txt_method = txt1.concat(txt2)  # Retorna "Hello World"

index_e = txt.index("e")  # Retorna o índice onde 'e' aparece pela primeira vez (1)
```
## ESTRUTURAS DE DADOS
```python

### Listas

my_list = ["apple", "banana", "cherry"]
print(my_list)  # Saída: ['apple', 'banana', 'cherry']

### Dicionários

my_dict = {"nome": "João", "idade": 30, "cidade": "São Paulo"}

### Conjuntos

my_set = {1, 2, 3, 4, 5}

### Tuplas

my_tuple = (1, 2, 3, 4, 5)
```
## IF
```python

time = 20
if time < 18:
    print("Good day.")
else:
    print("Good evening.")

time = 20
result = "Good day." if time < 18 else "Good evening."  # versão simplificada
```
## WHILE
```python

i = 0
while i < 5:
    print(i)
    i += 1
```
## FOR
```python

for i in range(5):
    print(i)
```
## FUNÇÕES
```python

def my_function():
    print("Hello")

def add(x, y):
    return x + y
```
## CLASSES / OBJETOS
```python

class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def print_info(self):
        print("Name:", self.name, ", Age:", self.age)

# Criação de um objeto
person1 = Person("John", 30)
person1.print_info()  # Imprime "Name: John, Age: 30"
```
## TRATAMENTO DE EXCEÇÕES
```python

try:
    # Bloco de código que pode gerar uma exceção
except Exception as e:
    # Bloco de código para tratar a exceção
finally:
    # Bloco de código a ser executado independentemente de uma exceção ser lançada ou não
```
