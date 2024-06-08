## PYTHON

*print ("__")* - imprimir


# - comentários


""" - várias linhas de comentários """


## VARIÁVEIS LIVRES

carname = "Volvo" 
d = 50
x, y, z = "banana", "maça", "uva"



## TIPOS 

*bool (0)* - False
*bool (1*) - True

*int* - 1,2,3,4,....

*str* - 'ola' ou "ola"

*float* - 0.2

*list* - [1, 2, 3, 4, 5] coleção ordenada e mutável de elementos
*tuple* - (1, 2, 3, 4, 5) sequência ordenada e imutável de elementos
*set* - {1, 2, 4, 3, 5} coleção não ordenada e mutável de elementos únicos
*dict* - {"nome": "João", "idade": 30, "cidade": "São Paulo"} coleção não ordenada e mutável, representado por um par chave-valor



## STRINGS

*txt.capitalize()* - converte o primeiro caractere para maiúscula
*txt.split()* - divide a string em uma lista de substrings
*" ".join(iterable)* - junta os elementos de um iterable (como uma lista) em uma string, separados por um espaço
*txt.startswith(prefix)* - verifica se a string começa com o prefixo especificado
*txt.endswith(suffix)* - verifica se a string termina com o sufixo especificado

age = 36
txt = "_ age is {}"
print(*txt.format(age)*)



## LIST

*list.append("_")* - adicionar à lista
*list.insert(1, "a")* - inserir no índice 1
*list.remove("_")* - remover da lista
*list[-1]* - última posição (len-1)
*list[2:5]* - índices de 2 a 4, terceiro, quarto e quinto elementos
*len(list)* - tamanho da lista



## SET

*set.update(lista)* - acrescentar a lista ao set
*set.discard("_")* - remover elemento do set



## DICTIONARY

*car={"a": _, "b": _}*

*print(car.get("a"))* - imprime a chave "a" e o valor correspondente
*car["a"] = "c"* - muda o valor associado à chave "a" para "c"
*car["d"] = "_"* - acrescenta a chave "d" e o valor ao dicionário
*car.pop("b")* - remove a chave "b"
*car.clear()* - limpa todo o dicionário



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
        *break*; - para o loop 

while (___):
    _____
    if____:
        *continue*; - passa para a próxima iteração
    _____



## FOR

*for x in enumerate(iterable)* - para cada elemento e seu índice em um iterável
*for x in range(6)* - para cada número de 0 a 5



## FUNÇÕES

*def my_function():* - definição de função básica
______
*return* _

*def my_function(*args, *kwargs):* - aceita um número variável de argumentos posicionais (*args) e argumentos de palavra-chave (*kwargs**)
______



## LAMBDA

*x = lambda a: a* - toma o argumento a e retorna-o



## CLASSES

*class MyClass:* - definição de classe
x = 5
p1 = MyClass()

print(p1.x)


*class Person:*
*def __init__(self, name, _, _):* - função de inicialização

self.name = name 
self._ = _  
self._ = _  

def printName(self):
    print(self.name)

*class Student(Person):*  - HERANÇA
x = Student("Mike")
x.printName()



## MODULOS

*import module* - importa um módulo inteiro
*import module as alias* - importa um módulo com um alias
*from module import name* - importa um nome específico de um módulo
*print(dir(module))* - imprime todas as variáveis e nomes das funções do módulo
*from package import module* - importa um módulo de um pacote
*from package.module import name* - importa um nome específico de um módulo em um pacote
