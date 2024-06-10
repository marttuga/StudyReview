
## C 

```c
int main() {
    printf("Hello World!");
    return 0;
}
```

// This is a single-line comment

/* This is a multi-line comment */

## VARIABLES

```c
const int myNum = 15; // constante nao pode mudar
int myNum = 15;
printf("%d", myNum);

float myFloatNum = 5.9;
printf("%.1f", myFloatNum);

char myLetter = 'D';
printf("%c", myLetter);
```

## STRINGS

```c
char myString[] = "Hello";
printf("%s", myString);

// Funções de strings comuns
strlen(myString); // Retorna o comprimento da string
strcpy(dest, src); // Copia src para dest
strcat(dest, src); // Concatena src para dest
strcmp(str1, str2); // Compara duas strings
```

## ARRAYS

```c
int myNumbers[] = {25, 50, 75, 100};
printf("%d", myNumbers[0]); // Acessa o primeiro elemento do array

// Iterar sobre um array
for (int i = 0; i < 4; i++) {
    printf("%d\n", myNumbers[i]);
}
```

## POINTERS

```c
int myVar = 25;
int *ptr = &myVar;

printf("%p", ptr); // Imprime o endereço de myVar
printf("%d", *ptr); // Imprime o valor de myVar via ponteiro

// Manipulação de ponteiros
int x = 5;
int *p = &x;
*p = 10; // Altera o valor de x para 10
```

## STRUCTURES

```c
struct Person {
    char name[50];
    int age;
};

struct Person person1;
strcpy(person1.name, "John");
person1.age = 30;

printf("Name: %s, Age: %d", person1.name, person1.age);
```

## OPERATORS

```c
int x = 5;
int y = 3;
printf("%d", x + y); // Adição
printf("%d", x - y); // Subtração
printf("%d", x * y); // Multiplicação
printf("%d", x / y); // Divisão
printf("%d", x % y); // Módulo

x++; // Incremento
y--; // Decremento

// Operadores lógicos
(x < 5 && y > 2); // E lógico
(x < 5 || y > 2); // OU lógico
!(x < 5); // NÃO lógico
```

## IF

```c
int time = 20;
if (time < 18) {
    printf("Good day.");
} else {
    printf("Good evening.");
}

// Versão simplificada
(time < 18) ? printf("Good day.") : printf("Good evening.");
```

## SWITCH

```c
int day = 4;
switch (day) {
    case 1:
        printf("Sunday");
        break;
    case 2:
        printf("Monday");
        break;
    case 3:
        printf("Tuesday");
        break;
    case 4:
        printf("Wednesday");
        break;
    case 5:
        printf("Thursday");
        break;
    case 6:
        printf("Friday");
        break;
    case 7:
        printf("Saturday");
        break;
    default:
        printf("Invalid day");
}
```

## LOOPS - WHILE FOR

### WHILE

```c
int i = 0;
while (i < 5) {
    printf("%d\n", i);
    i++;
}
```

### FOR

```c
for (int i = 0; i < 5; i++) {
    printf("%d\n", i);
}
```

## FUNÇÕES

```c
void myFunction() {
    printf("I just got executed!");
}

int add(int a, int b) {
    return a + b;
}

int main() {
    myFunction();
    int result = add(5, 3);
    printf("%d", result);
    return 0;
}
```
