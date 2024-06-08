*PYTHON*

*print ("__")* - imprimir

# - comentários

""" - várias linhas de comentários
"""

*VARIÁVEIS LIVRES*

carname = "Volvo" 
d = 50
x, y, z = "banana", "maça", "uva"

*TIPOS* 

*bool (0)* - False
*bool (1*) - True

*int* - 1,2,3,4,....

*str* - 'ola' ou "ola"

*float* - 0.2

*list* - [1, 2, 3, 4, 5] coleção ordenada e mutável de elementos
*tuple* - (1, 2, 3, 4, 5) sequência ordenada e imutável de elementos
*set* - {1, 2, 4, 3, 5} coleção não ordenada e mutável de elementos únicos
*dict* - {"nome": "João", "idade": 30, "cidade": "São Paulo"} coleção não ordenada e mutável, representado por um par chave-valor

*STRINGS*

*txt.len()* - comprimento
*txt[0]* - index 0 1º posiçao
*txt[2:5]* - do index 2 ao 4
*txt.strip(*) - tirar espaços brancos
*txt.upper()* - para maiusculo
*txt.lower()* - para minusculo
*txt.replace( "a" , "b"*) - substitui o a pelo b

age = 36
txt = "_ age is {}"
print(*txt.format(age)*)

*LIST*

*list.append( "_" )* - adicionar à lista
*list.insert( 1 , "a" )* - inserir no index 1
*list.remove( "_" )* - remover da lista
*list[-1]* - ultima posiçao (len-1)
*list[2:5]* - index 2-5 , 3º, 4º e 5º elementos
*len( list )* - tamanho da lista

**SET

*set.update( lista )* - acrescentar a lista ao set
*set.discard( "_" )* - remover elemento do set

*DICTIONARY*

*car={ "a": _ , "b": _ }*

*print(car.get( "a" ))* - imprime o a e o valor
*car[ "a" ] = "c"* - muda a para c
*car[ "d" ] = "_"* - acrescenta o d e o valor ao dicionario
*car.pop( "b" )* - remove o b
*car.clear()* - limpa o dict todo

*IF* 

if a > b:
____
    elif a==b:
    _____
        else:
        ______


*WHILE*

while (___):
_____
    if____:
    *break*; - parar o loop 

while (___):
_____
    if____:
    *continue*; - passa à próxima ação

while (___):
_____
    else:
    ____


*FOR*

*for x in list* - por cada x na lista
*for x in range(6)* - por cada x 6vezes no loop


*FUNÇOES*

*def my_function():* - definiçao da funçao normal
______
*return* _

*def my_function():* - nao se sabe o nº de argumentos
*def my_function(* x):** - nº de keywords

*LAMBDA*

*x= lambda a:a* - toma o a e retorna-o


*CLASSES*

*class MyClass:* -definiçao da classe
x = 5
p1 = MyClass()

print( p1.x )


*class Person:*
*def _init_( name, _ , _ ):* - init function

self.name = name 
self._ = _  
self._ = _  

def printName(self):
print( self.name )

*class Student(Person):*  - INHERITANCE
x = Student("Mike")
x.printName()

*MODULOS*

*import myModule* - importar
*import myModule as m* - renomear
*print( dir( myModule ) )* - imprime todas as variaveis e nomes das funçoes
*from myModule import "__"* - importar so um especifico