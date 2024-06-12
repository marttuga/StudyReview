## JAVASCRIPT

## VARIAVEIS

```javascript
let carName = "Volvo";

let x=50;
let y = 10;
document.getElementById("demo").innerHTML = x + y;

let z = x + y;
alert(z);
```

## OPERADORES
```javascript
alert(10 * 5);

alert(10 / 5);

alert(10 % 5);

x+=y

x*=y

```


## TIPOS DE DADOS

```javascript
Number - 

String - 

Object - 
```

## FUNÇOES
```javascript
function myFunction() {
  alert("Hello World!");
}
myFunction();
____________________
function myFunction() {
  return "Hello";
}
document.getElementById("demo").innerHTML = myFunction();
______________________
function myFunction() {
    document.getElementById("demo").innerHTML ="Hello";
}
```

## OBJETOS
```javascript
const person = {
  name : "John", 
  age : 50
};

alert( person.name + " is " + person.age );
```


## EVENTS
```javascript
<button onclick = "alert('Hello')">Click me.</button>

<button **onclick** = "myFunction()">Click me.</button>

<div **onmouseover**="this.style.backgroundColor='red'">myDIV.</div>
```
## STRINGS
```javascript
let txt1 = "Hello World!";
let x = txt1.length;
alert(x);

let txt2 = "We are \"Vikings\"";

alert(txt1 + txt2);

txt1.toUpperCase();
txt1.toLowerCase();

let y = txt1.slice(6,11 );

txt = txt1.("Hello", "Welcome");
```
## ARRAY
```javascript
const cars = ["Saab", "Volvo", "BMW"];

let x = cars[1];

cars[0] = "Ford";

alert(cars.length);

cars.pop();

cars.push("Fiat");

cars.splice(1,2); 

cars.sort();
```

## DATES
```javascript
const d = new Date();
alert(d);

year = d.getFullYear();
month = d.getMonth();

d.setFullYear(2020);
```

## MATH

```javascript
let r = Math.random();
let x = Math.max(10,20);
let y = Math.round(5.3);
let s = Math.sqrt(9);
```

## COMPARISONS
```javascript
x>y
x==y
x!=y

var age = n;
var voteable = (age < 18) ? "Too young" : "Old enough";
alert(voteable);
```

## CONDITIONS
```javascript

if (x > y){ 
  alert("Hello World");
} else {
    alert("Goodbye");
}

```

## SWITCH 

```javascript
switch(fruits) {
   case "Banana":
    alert("Hello")
    break;
   case "Apple":
    alert("Welcome")
    break;   
   default:
    alert("Neither"); 
}
```

## FOR

```javascript
let i;
for(i = 0 ; i < 10 ; i++ ) {

  console.log(i);
  if (i == 5) {
    break ;
  }
}
___________
const fruits = ["Apple", "Banana", "Orange"];

for (x in fruits) {
  if (i == 5) {
    continue ;
  }
  console.log(x);
}
```
## WHILE

```javascript
let i = 0;
while(i < 10) {
  console.log(i);
  i++
}
```
## HTML DOM

```javascript
<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML = "Hello";
</script>
______________
<p id="demo"></p>

<script>
document.getElementsByTagName("p")[0].innerHTML = "Hello";
</script>
______________
<p class="test"></p>
<p class="test"></p>

<script>
document.getElementsByClassName("test")[0].innerHTML = "Hello";
</script>
_______________
<img id="image" src="smiley.gif">

<script>
document.getElementById("image").src = "pic_mountain.jpg";
</script>
______________
<input type="text" id="myText" value="Hello">

<script>
document.getElementById("myText").value = "Have a nice day!";
</script>
______________
<p id="demo"></p>

<script>
document.getElementById("demo").style.color = "red";
</script>
______________
<p id="demo"></p>

<script>
document.getElementById("demo").style.fontSize = "40px";
</script>
______________
<p id="demo"></p>

<script>
document.getElementById("demo").style.display = "none";
</script>
______________
<button id="demo">Click me1</button>

<script>
document.getElementById("demo").addEventListener("click", myFunction);
</script>
```
