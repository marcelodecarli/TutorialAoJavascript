# Tutorial ao Javascript

## O que iremos aprender?
Aqui iremos aprender sobre a linguagem de programação Javascript.

## O que é Javascript?
Javascript é uma linguagem de programação, largamente utilizada em aplicções web atualmente. Ela permite a implementação de elementos complexos em sites, como por exemplo, conteúdo que se atualiza dinamicamente, mapas interativos, gráficos animados entre outros. É considera uma das principais linguagens da web.

## Configuração do ambiente:

1. Primeiro devemos verificar se temos instalado no computador o Node.js. Para essa verificação no windows utilizamos no terminal de comando (CMD) o comando:
   ```
    node --version
   ```
  Caso não tenha instalado o Node.js pode baixar no link: https://nodejs.org/en/download/
  
2. Em seguida devemos verificar se temos instalada a IDE mais conhecida atualmente é o Visual Studio Code. Para essa verificação no windows utilizamos no terminal de comando (CMD) o comando:

   ```
   code --version
   ```
     Caso não tenha instalado o Node.js pode baixar no link e escolha seu sistema operacional:
   https://code.visualstudio.com/Download

## Sintaxe básica:

Temos como sintaxe básica os itens abaixo:
-Tipos de dados;
- Declaração de variáveis;
- Operadores;
- Estruturas condicionais;
- Estruturas de repetição.

## Tipos de dados:

### Strings:
Strings são usadas para representar texto e devem ser declaradas entre aspas simples ou duplas.

- Let: Temos a declaração nessa variável dados que podemos alterar posteriormente;

__Exemplo de declaração de variável do tipo string utilizando let:__

 Nesse exemplo temos como nome da variável **name** e o valor atribuida a ela **"Marcelo"**
 
 ```
let name = "Marcelo"
console.log(name); // Marcelo
 ```

- Const: temos a declaração de variáveis que são constantes. Isso mesmo, você não entende errado, são variáveis que atribuimos valores que __não__ poderão ser alterados posteriormente.

     __Exemplo de declaração de variável do tipo string utilizando const:__

 Nesse exemplo temos como nome da constante **fruta** e o valor atribuida a ela **"laranja"**
 ```
const fruta = "laranja"
console.log(fruta); // laranja
 ```
---

### Números:

Números são usados para representar valores numéricos e podem ser inteiros ou de ponto flutuante.

__Exemplo de declaração de variável do tipo number utilizando let:__

- Let: Temos a declaração nessa variável dados que podemos alterar posteriormente;
 ```
let numero = 10 // inteiro
console.log(numero); // 10
let number = 5.50 // com ponto flutuante
console.log(number); // 5.50
 ```

__Exemplo de declaração de variável do tipo number utilizando const:__

- Const: temos a declaração de variáveis que são constantes. Isso mesmo, você não entende errado, são variáveis que atribuimos valores que __não__ poderão ser alterados posteriormente.
 ```
const numero = 1250 // inteiro
console.log(numero); // 1250
const number = 321.50 // com ponto flutuante
console.log(number); // 321.50
 ```
---

### Valores booleanos:
Valores booleanos podem ser true ou false e são usados em expressões lógicas e estruturas de controle.

```
let estaFrio = true
let estaQuente = false
```
---
### Undefined:
Undefined é usado para variáveis que foram declaradas, mas não possuem um valor atribuído.

```
let nome; 
console.log(nome); // undefined
```
---
### Null:
Null é usado para indicar a ausência de valor.

```
let variavel = null; // null
```
---
### Objetos:
Objetos são estruturas de dados com múltiplas propriedades e podem ser acessados utilizando a sintaxe de ponto ou de colchetes.

```
let pessoa = {
  nome: 'Marcelo',
  idade: 33
};
console.log(pessoa) // {nome: 'Marcelo', idade: 33}
```
---
### Arrays:
Arrays são usados para armazenar coleções de valores em uma única variável.
 ```
let lista = [1, 2, 'testando', 6, 'laranja']
console.log(lista) // [1, 2, 'testando', 6, 'laranja']
```
---
### Funções:
Funções são blocos de código que podem ser reutilizados e executados quando necessário.
```
function nomeDaFuncao(atributo) {
   console.log(atributo)
   }

console.log(nomeDaFuncao('Marcelo')); //Marcelo
```
---
### Operadores:
Os operadores são usados para realizar operações em variáveis e valores. Os operadores aritméticos mais comuns em JavaScript são a adição `(+)`, subtração `(-)`, multiplicação `(*)`, divisão `(/)` e módulo `(%)`. Há também operadores de comparação `(==, !=, ===, !==, <, >, <=, >=)` e operadores lógicos `(&&, ||, !)`.

Exemplo:
```
let x = 5;
let y = 10;
let z = x + y; // soma
let w = x * y; // multiplicação
let a = x == y; // comparação
let b = x && y; // operador lógico
```

## Estruturas de repetição:

As estruturas de repetição são usadas para repetir um bloco de código várias vezes. Dessa forma a estrutura de repetição mais comum é o “for”, que executa um bloco de código um número específico de vezes. Há também o “while” e o “do-while”, que executam um bloco de código enquanto uma condição for verdadeira.

Exemplo:
```
for (let i = 0; i < 10; i++) {
  console.log(i);
}
```
---
```
let i = 0;
while (i < 10) {
  console.log(i);
  i++;
}
```
---
```
let i = 0;
do {
  console.log(i);
  i++;
} while (i < 10);
```
---
### Estruturas condicionais:

A princípio, as estruturas condicionais são usadas para tomar decisões em um programa. A estrutura condicional mais comum é o “if”, que executa um bloco de código se uma condição for verdadeira. Sendo assim, há também o “else if” e o “else”, que são usados para executar blocos de código alternativos se a primeira condição não for atendida.

Exemplo:

```
var x = 5;
var y = 10;
if (x < y) {
  console.log("x é menor que y");
} else if (x > y) {
  console.log("x é maior que y");
} else {
  console.log("x é igual a y");
}
```
---
