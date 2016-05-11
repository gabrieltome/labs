# Aula Especial - ES6

## Escopo

Em **JavaScript**, **só temos escopo a nível de função**.

## Hoisting

###Variable Hoisting

Toda vez que uma variável é definida, sua **declaração** é **hoisted**, mas **não sua inicialização**.

`Apenas a declaração da variável é HOISTED!!!`

###Function Hoisting

Tanto o **nome da função** como o **corpo da função** são **hoisted**.

## let

Quando usamos **let**, não ocorre **hoisting**.

O **let** cria a variável dentro do escopo da variável.

Exemplo

```
'use strict';

let a = 1;
console.log(a);
```

` Não podemos re-declarar váriaveis com 'let'`
 

## const

Cria uma **constante** que pode pertencer ao escopo global ou local de uma função.

Constantes são **block-scoped**.

O valor de uma constante **não** pode ser alterado via re-atribuição, e uma constante não pode ser re-declarada.

É **obrigatório** que um valor seja atribuido à constante em sua declaração.

Uma constante não deve compartilhar o nome com uma função ou variável em um mesmo escopo.

## Arrow Function

Uma **Arrow Function** é uma função que possui uma **sintaxe mais curta** quando comparada com uma função normal, vunculando o valor de **this** de maneira léxica.

`Arrow Functions sempre são anônimas`.

**Funcão normal:** `function(x) { return x; }`

**Arrow Function:** `(x) => x;`

Retornando um **objeto**: `() => ({})`

