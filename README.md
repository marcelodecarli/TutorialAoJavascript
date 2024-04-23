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

### Undefined:
Undefined é usado para variáveis que foram declaradas, mas não possuem um valor atribuído.

```
let nome; 
console.log(nome); // undefined
```

### Null:
Null é usado para indicar a ausência de valor.

```
let variavel = null; // null
```

### Objetos:
Objetos são estruturas de dados com múltiplas propriedades e podem ser acessados utilizando a sintaxe de ponto ou de colchetes.

```
let pessoa = {
  nome: 'Marcelo',
  idade: 33
};
console.log(pessoa) // {nome: 'Marcelo', idade: 33}
```

### Arrays:
Arrays são usados para armazenar coleções de valores em uma única variável.
 ```
let lista = [1, 2, 'testando', 6, 'laranja']
console.log(lista) // [1, 2, 'testando', 6, 'laranja']
```

### Funções:
Funções são blocos de código que podem ser reutilizados e executados quando necessário.

function nomeDaFuncao(atributo) {
   console.log(atributo)
   }

console.log(nomeDaFuncao('Marcelo')); //Marcelo



