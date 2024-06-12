## JAVASCRIPT

## VARIAVEIS

```javascript
// Declarar uma variável let chamada 'carName' e atribuir o valor "Volvo"
let carName = "Volvo";

// Declarar variáveis let 'x' e 'y' e atribuir valores 50 e 10 respectivamente
let x = 50;
let y = 10;

// Somar x e y, e exibir o resultado no elemento com id "demo"
document.getElementById("demo").innerHTML = x + y;

// Declarar a variável let 'z' e atribuir o resultado da soma de x e y
let z = x + y;

// Exibir um alerta com o valor de z
alert(z);

```

## OPERADORES
```javascript
// Exibir um alerta com o resultado da multiplicação de 10 por 5
alert(10 * 5);

// Exibir um alerta com o resultado da divisão de 10 por 5
alert(10 / 5);

// Exibir um alerta com o resto da divisão de 10 por 5
alert(10 % 5);

// Adicionar o valor de y a x e atribuir o resultado a x
x += y;

// Multiplicar x por y e atribuir o resultado a x
x *= y;


```


## TIPOS DE DADOS

```javascript
// Number
let idade = 25; // Inteiro
let altura = 1.75; // Decimal

// String
let nome = "João";
let saudacao = "Olá, mundo!";

// Object
const pessoa = {
  nome: "Maria",
  idade: 30,
  cidade: "Lisboa"
};

```

## FUNÇOES
```javascript
// Função que exibe um alerta com a mensagem "Hello World!"
function myFunction() {
  alert("Hello World!");
}
myFunction();

// Função que retorna a string "Hello"
function myFunction() {
  return "Hello";
}
// Exibir o retorno da função no elemento com id "demo"
document.getElementById("demo").innerHTML = myFunction();

// Função que altera o conteúdo do elemento com id "demo" para "Hello"
function myFunction() {
  document.getElementById("demo").innerHTML = "Hello";
}

```

## OBJETOS
```javascript
// Definir um objeto constante 'person' com propriedades 'name' e 'age'
const person = {
  name: "John",
  age: 50
};

// Exibir um alerta com o nome e a idade da pessoa
alert(person.name + " is " + person.age);

```


## EVENTS
```javascript
// Botão que exibe um alerta com a mensagem "Hello" ao ser clicado
<button onclick="alert('Hello')">Click me.</button>

// Botão que chama a função myFunction() ao ser clicado
<button onclick="myFunction()">Click me.</button>

// Div que altera a cor de fundo para vermelho ao passar o rato por cima
<div onmouseover="this.style.backgroundColor='red'">myDIV.</div>

```
## STRINGS
```javascript
// Declarar uma variável let 'txt1' e atribuir o valor "Hello World!"
let txt1 = "Hello World!";
// Obter o comprimento da string e armazenar em x
let x = txt1.length;
alert(x);

// Declarar uma variável let 'txt2' com a string incluindo aspas
let txt2 = "We are \"Vikings\"";

// Concatenar as strings txt1 e txt2 e exibir o resultado
alert(txt1 + txt2);

// Converter txt1 para letras maiúsculas
txt1.toUpperCase();
// Converter txt1 para letras minúsculas
txt1.toLowerCase();

// Extrair uma parte da string de índice 6 a 11
let y = txt1.slice(6, 11);

// Substituir "Hello" por "Welcome" em txt1
txt = txt1.replace("Hello", "Welcome");

```
## ARRAY
```javascript
// Definir um array constante 'cars' com três elementos
const cars = ["Saab", "Volvo", "BMW"];

// Acessar o segundo elemento do array
let x = cars[1];

// Alterar o primeiro elemento do array
cars[0] = "Ford";

// Exibir o comprimento do array
alert(cars.length);

// Remover o último elemento do array
cars.pop();

// Adicionar um novo elemento ao final do array
cars.push("Fiat");

// Remover 2 elementos a partir do índice 1
cars.splice(1, 2);

// Ordenar os elementos do array
cars.sort();

```

## DATES
```javascript
// Criar um novo objeto Date
const d = new Date();
alert(d);

// Obter o ano atual
let year = d.getFullYear();
// Obter o mês atual (0-11)
let month = d.getMonth();

// Definir o ano para 2020
d.setFullYear(2020);

```

## MATH

```javascript
// Gerar um número aleatório entre 0 e 1
let r = Math.random();
// Obter o maior valor entre 10 e 20
let x = Math.max(10, 20);
// Arredondar 5.3 para o inteiro mais próximo
let y = Math.round(5.3);
// Calcular a raiz quadrada de 9
let s = Math.sqrt(9);

```

## COMPARISONS
```javascript
// Comparar se x é maior que y
x > y;
// Comparar se x é igual a y
x == y;
// Comparar se x é diferente de y
x != y;

// Usar o operador ternário para verificar a idade
var age = n;
var voteable = (age < 18) ? "Too young" : "Old enough";
alert(voteable);

```

## CONDITIONS
```javascript
// Estrutura if-else para verificar se x é maior que y
if (x > y) {
  alert("Hello World");
} else {
  alert("Goodbye");
}

```

## SWITCH 

```javascript
// Estrutura switch para verificar o valor da variável 'fruits'
switch (fruits) {
  case "Banana":
    alert("Hello");
    break;
  case "Apple":
    alert("Welcome");
    break;
  default:
    alert("Neither");
}

```

## FOR

```javascript
// Loop for que itera de 0 a 9 e interrompe quando i é igual a 5
let i;
for (i = 0; i < 10; i++) {
  console.log(i);
  if (i == 5) {
    break;
  }
}

// Loop for-in para iterar sobre os índices do array 'fruits'
const fruits = ["Apple", "Banana", "Orange"];
for (x in fruits) {
  if (i == 5) {
    continue;
  }
  console.log(x);
}

```
## WHILE

```javascript
// Loop while que itera enquanto i for menor que 10
let i = 0;
while (i < 10) {
  console.log(i);
  i++;
}

```
## HTML DOM

```javascript
// Alterar o conteúdo do elemento com id "demo" para "Hello"
<p id="demo"></p>
<script>
document.getElementById("demo").innerHTML = "Hello";
</script>

// Alterar o conteúdo do primeiro elemento <p> para "Hello"
<p id="demo"></p>
<script>
document.getElementsByTagName("p")[0].innerHTML = "Hello";
</script>

// Alterar o conteúdo do primeiro elemento com classe "test" para "Hello"
<p class="test"></p>
<p class="test"></p>
<script>
document.getElementsByClassName("test")[0].innerHTML = "Hello";
</script>

// Alterar o atributo src da imagem com id "image"
<img id="image" src="smiley.gif">
<script>
document.getElementById("image").src = "pic_mountain.jpg";
</script>

// Alterar o valor do campo de texto com id "myText"
<input type="text" id="myText" value="Hello">
<script>
document.getElementById("myText").value = "Have a nice day!";
</script>

// Alterar a cor do texto do elemento com id "demo" para vermelho
<p id="demo"></p>
<script>
document.getElementById("demo").style.color = "red";
</script>

// Alterar o tamanho da fonte do elemento com id "demo" para 40px
<p id="demo"></p>
<script>
document.getElementById("demo").style.fontSize = "40px";
</script>

// Ocultar o elemento com id "demo"
<p id="demo"></p>
<script>
document.getElementById("demo").style.display = "none";
</script>

// Adicionar um evento de clique ao botão com id "demo"
<button id="demo">Click me!</button>
<script>
document.getElementById("demo").addEventListener("click", myFunction);
</script>

```
