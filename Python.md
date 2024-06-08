## PYTHON

**print ("__")** - imprimir

# - comentários

**"""** - várias linhas de comentários **"""**

## VARIÁVEIS LIVRES

carname = "Volvo" 

d = 50

x, y, z = "banana", "maça", "uva"

## TIPOS 

**bool (0)** - False

**bool (1)**  - True

**int** - 1,2,3,4,....

**str** - 'ola' ou "ola"

**float** - 0.2

**list** - [1, 2, 3, 4, 5] 
    - Coleção ordenada e mutável de elementos

**tuple** - (1, 2, 3, 4, 5) 
    - Sequência ordenada e imutável de elementos

**set** - {1, 2, 4, 3, 5} 
    - Coleção não ordenada e mutável de elementos únicos

**dict** - {"nome": "João", "idade": 30, "cidade": "São Paulo"} 
    - Coleção não ordenada e mutável, representada por um par chave-valor

## STRINGS

**txt.capitalize()** 
    - Converte o primeiro caractere para maiúscula

**txt.split()** 
    - Divide a string em uma lista de substrings

**" ".join(iterable)** 
    - Junta os elementos de um iterable (como uma lista) em uma string, separados por um espaço

**txt.startswith(prefix)** 
    - Verifica se a string começa com o prefixo especificado

**txt.endswith(suffix)** 
    - Verifica se a string termina com o sufixo especificado

age = 36

txt = "_ age is {}"

print(**txt.format(age)**)

## LIST

**list.append("_")** 
    - Adicionar à lista

**list.insert(1, "a")** 
    - Inserir no índice 1

**list.remove("_")** 
    - Remover da lista

**list[-1]** 
    - Última posição (len-1)

**list[2:5]** 
    - Índices de 2 a 4, terceiro, quarto e quinto elementos

**len(list)** 
    - Tamanho da lista

## SET

**set.update(lista)** 
    - Acrescentar a lista ao set

**set.discard("_")** 
    - Remover elemento do set

## DICTIONARY

**car={"a": _, "b": _}**

**print(car.get("a"))** 
    - Imprime a chave "a" e o valor correspondente

**car["a"] = "c"** 
    - Muda o valor associado à chave "a" para "c"

**car["d"] = "_"** 
    - Acrescenta a chave "d" e o valor ao dicionário

**car.pop("b")** 
    - Remove a chave "b"

**car.clear()** 
    - Limpa todo o dicionário

## IF 

if a > b:

    ___

elif a == b:

    _____

else:

    ______

## WHILE

while (___):

    _____

    if____:

        **break**; 

            - Para o loop 

while (___):

    _____

    if____:

        **continue**; 

            - Passa para a próxima iteração

    _____

## FOR

**for x in enumerate(iterable)** 
    - Para cada elemento e seu índice em um iterável

**for x in range(6)** 
    - Para cada número de 0 a 5

## FUNÇÕES

**def my_function():** 
    - Definição de função básica

______

**return** _

**def my_function(*args, *kwargs):** 
    - Aceita um número variável de argumentos posicionais (*args) e argumentos de palavra-chave (*kwargs**)

______

## LAMBDA

**x = lambda a: a** 
    - Toma o argumento a e retorna-o

## CLASSES

**class MyClass:** 
    - Definição de classe

x = 5

p1 = MyClass()

print(p1.x)

**class Person:**

**def __init__(self, name, _, _):** 
    - Função de inicialização

self.name = name 

self._ = _  

self._ = _  

def printName(self):

    print(self.name)

**class Student(Person):**  
    - Herança

x = Student("Mike")

x.printName()

## MODULOS

**import module** 
    - Importa um módulo inteiro

**import module as alias** 
    - Importa um módulo com um alias

**from module import name** 
    - Importa um nome específico de um módulo

**print(dir(module))** 
    - Imprime todas as variáveis e nomes das funções do módulo

**from package import module** 
    - Importa um módulo de um pacote

**from package.module import name** 
    - Importa um nome específico de um módulo em um pacote
