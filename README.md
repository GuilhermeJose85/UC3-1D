# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 


## Conteúdo Técnico
Escreva aqui os conteúdos aprendidos.
## Variaveis

*var*:
Descrição: É a forma mais antiga de declarar variáveis em JavaScript. A palavra-chave var é funcionalmente equivalente a let e const, mas tem um escopo de função em vez de bloco, o que pode causar alguns problemas inesperados.
Exemplo:

```js
var idade = 30;
console.log(idade); // 30
```

*let*:
Descrição: Introduzido no ES6 (ECMAScript 2015), let permite declarar variáveis com escopo de bloco, o que significa que elas são visíveis apenas dentro do bloco { } em que foram declaradas.
Exemplo:
```js
let nome = 'Maria';
if (true) {
    let nome = 'João';
    console.log(nome); // João
}
console.log(nome); // Maria
```
*const*
Descrição: Também introduzido no ES6, const é usado para declarar variáveis cujo valor não pode ser reatribuído depois de definido. Assim como let, const tem escopo de bloco.
Exemplo:
```js
const pi = 3.14159;
console.log(pi); // 3.14159
// pi = 3.14; // Isso causará um erro, pois não podemos reatribuir um valor a uma variável `const`
```
## Strings
Descrição: Strings são sequências de caracteres. Em JavaScript, você pode criar strings usando aspas simples ('), aspas duplas ("), ou crases (`) para template literals.

Exemplos:

```js
let saudacao = 'Olá, Mundo!'; // String com aspas simples
let nome = "Maria"; // String com aspas duplas
let mensagem = `Bem-vinda, ${nome}`; // String com template literal e interpolação
```

 ## Number
Descrição: Números em JavaScript podem ser inteiros ou flutuantes e são usados para representar valores numéricos.

Exemplos:
```js
let idade = 30; // Número inteiro
let altura = 1.75; // Número flutuante
```

##Concatenação de Strings*
Descrição: A concatenação é o processo de unir duas ou mais strings. Pode ser feito com o operador + ou usando template literals.

Exemplos:

```js
let primeiroNome = 'João';
let sobrenome = 'Silva';

// Usando o operador +
let nomeCompleto = primeiroNome + ' ' + sobrenome; // "João Silva"

// Usando template literals
let nomeCompletoTemplate = `${primeiroNome} ${sobrenome}`; // "João Silva"
```
## Estruturas Condicionais if-else
Descrição: As estruturas if-else permitem executar diferentes blocos de código com base em condições. Usadas para lógica condicional.

Exemplos:

```js
let idade = 18;

if (idade < 18) {
    console.log('Menor de idade');
} else if (idade === 18) {
    console.log('Você acabou de atingir a maioridade');
} else {
    console.log('Maior de idade');
```
 ## prompt
Descrição: A função prompt exibe uma caixa de diálogo que solicita ao usuário que insira um valor. O valor inserido é retornado como uma string.

Exemplos:

```js
let nome = prompt('Qual é o seu nome?');
console.log(`Olá, ${nome}!`);
```


## Atividades desenvolvidas
Escreva aqui as atividades desenvolvidas em sala e para casa. Você pode detelhar a atividade e usar links das atividades do codepen e vídeos desenvolvidos em sala. 
```js
const nome = "Guilherme";
const sobrenome = "José";
const fullName = nome + " " + sobrenome; 

console.log("Nome completo: " + fullName);

const a = 7
const b = 41
const soma=(a+b)

console.log(soma)

const p = 78
const k = 48
const subtrair=(p-k)

console.log(subtrair)

const x = 5
const y = 45
const multiplicar=(x*y)

console.log(multiplicar)

const i = 25
const q = 5
const dividir=(i/q)

console.log(dividir)


let o = 10;
let ç = 20;
let area = o * ç; 

console.log("Área do retângulo: " + area + " metros quadrados."); 

var greeting = "Olá, ";
var userName = "Maria";
var welcomeMessage = greeting + userName + "!"; 

console.log(welcomeMessage); 

const radius = 14;
const pi = 3.1415;
const circumference = 4 * pi * radius; 

console.log("A circunferência é: " + circumference + " unidades."); 

let price = 100;
let discount = 20;
let finalPrice = price - discount;

let message = "O preço final após o desconto é de " + finalPrice + " reais."; 

console.log(message);
https://codepen.io/Guilherme-Jos-/pen/Bagwyjd
