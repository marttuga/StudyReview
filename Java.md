## JAVA

```java
public class MyClass {

    public static void main(String[] args) {

        // Imprime "Hello World"
        System.out.println("Hello World");
    }
}

// - Comentário

/* 
   Várias
   linhas
   de
   comentário
*/

## TIPOS DE DADOS

int myNum = 9;

float myFloatNum = 8.99f;

char myLetter = 'A';

boolean myBool = false;

String myText = "Hello World";

// Tipos primitivos - byte, short, int, long, float, double, boolean e char

## OPERADORES

int x = 5;
int y = 3;

int result = x * y; // result será 15
result = x / y;     // result será 1

int z = 5;
z++;                // z será 6

int a = 10;
a += 5;             // a será 15

## STRINGS

String txt = "Hello";
int length = txt.length();              // Retorna o comprimento da string (5)
String upperCaseTxt = txt.toUpperCase();  // Retorna "HELLO"
String lowerCaseTxt = txt.toLowerCase();  // Retorna "hello"
String txt1 = "Hello";
String txt2 = " World";
String concatTxt = txt1 + txt2;         // Retorna "Hello World"
String concatTxtMethod = txt1.concat(txt2); // Retorna "Hello World"
int index = txt.indexOf("e");           // Retorna o índice onde 'e' aparece pela primeira vez (1)

## MATH

int x = 5;
int y = 10;
int max = Math.max(x, y);  // Retorna o maior valor entre x e y (10)
double sqrt = Math.sqrt(x); // Retorna a raiz quadrada de x (2.236...)
double rand = Math.random(); // Retorna um número aleatório entre 0 (inclusivo) e 1 (exclusivo)

## IF

int time = 20;
if (time < 18) {
    System.out.println("Good day.");
} else {
    System.out.println("Good evening.");
}

int time = 20;
String result = (time < 18)  "Good day." : "Good evening."; - versao simplificada


## SWITCH

int day = 4;
String dayString;
switch (day) {
    case 1:
        dayString = "Sunday";
        break;
    case 2:
        dayString = "Monday";
        break;
    case 3:
        dayString = "Tuesday";
        break;
    case 4:
        dayString = "Wednesday";
        break;
    case 5:
        dayString = "Thursday";
        break;
    case 6:
        dayString = "Friday";
        break;
    case 7:
        dayString = "Saturday";
        break;
    default:
        dayString = "Invalid day";
        break;
}

## WHILE

int i = 0;
while (i < 5) {
    System.out.println(i);
    i++;
}

## DO-WHILE

int j = 0;
do {
    System.out.println(j);
    j++;
} while (j < 5);

## FOR

for (int i = 0; i < 5; i++) {
    System.out.println(i);
}

## ARRAYS

int[] myArray = {1, 2, 3, 4, 5}; // Declaração e inicialização de um array
int[] newArray = new int[5]; // Declaração de um novo array
newArray[0] = 1; // Atribuição de valor ao primeiro elemento do novo array

// Operações com Arrays
int[] array1 = {1, 2, 3};
int[] array2 = {4, 5, 6};

int[] resultArray = new int[array1.length + array2.length];
System.arraycopy(array1, 0, resultArray, 0, array1.length);
System.arraycopy(array2, 0, resultArray, array1.length, array2.length);

## METHODS

// Método sem retorno e sem parâmetros
public void myMethod() {
    System.out.println("Hello");
}

// Método com retorno e com parâmetros
public int add(int x, int y) {
    return x + y;
}

// Método com sobrecarga
public double add(double x, double y) {
    return x + y;
}

// Chamada de método
myMethod();
int sum = add(5, 3);
double sumDouble = add(5.5, 3.3);

## CLASSES / OBJECTS

class Person {
    String name;
    int age;

    Person(String name, int age) {
        this.name = name;
        this.age = age;
    }

    void printInfo() {
        System.out.println("Name: " + name + ", Age: " + age);
    }
}

// Criação de um objeto
Person person1 = new Person("John", 30);
person1.printInfo(); // Imprime "Name: John, Age: 30"

## TRY CATCH

try {
    // Bloco de código que pode gerar uma exceção
} catch (Exception e) {
    // Bloco de código para tratar a exceção
}

