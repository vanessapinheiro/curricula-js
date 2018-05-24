# Quiz 2

- Tipo: `quiz`
- Formato: `self-paced`
- Duração: `30min`

***

## Perguntas

### 1) Que forma de modificar o fluxo de um programa mostra a figura a seguir?

![Flujo bucle](http://eloquentjavascript.net/img/controlflow-loop.svg)

#### Opções

1. while
2. loops em geral
3. if
4. if else
5. if else "aninhado" (nested)

<solution style="display:none;">2</solution>

### 2) Qual o problema com o código?

```js
do {
  console.log('Hello world');
} while (2 > 3);
```

#### Opções

1. Tem um erro de sintaxis
2. Não utiliza boas práticas
3. A variável não está bem declarada
4. Gera um loop infinito
5. Nenhum, funciona bem e imprime 'hello world' uma vez no painel

<solution style="display:none;">5</solution>

### 3) Encontre o erro na função

```js
var result = 0;

var showSum = function(num1, num2) {
  result = num1 + num2;
  alert('El resultado es ' + result);
}

showSum(if, else);
```

#### Opções

1. A função não está sendo invocada
2. Os parâmetros não estão sendo declarados
3. alert não é uma função
4. Erro de sintaxis. Não se pode utilizar keywords como argumentos

<solution style="display:none;">4</solution>

### 4) A diferença entre undefined e null

#### Opções

1. Não existe, são a mesma coisa 
2. Não importa
3. `undefined` não tem valor e `null` é um string vazio
4. `undefined` significa que não foi _assinalado_ um valor, enquanto `null`
   significa que foi _assinalado_ o valor `null`

<solution style="display:none;">4</solution>

### 5) Qual o resultado de

```js
var number = 0;
while (number <= 12) {
  console.log(number);
  number = number + 2;
}
```

#### Opções

1. imprime os números pares de 0 a 10 (inclusive)
2. imprime os números pares de 0 a 12 (inclusive)
3. imprime os números pares de 2 a 10 (inclusive)
4. imprime os números pares de 2 a 12 (inclusive)

<solution style="display:none;">2</solution>

### 6) O resultado de "Hola" + "mundo" é

#### Opções

1. "Hola Mundo"
2. "Hola mundo"
3. "Holamundo"
4. 'HolaMundo'

<solution style="display:none;">3</solution>

### 7) Qual o resultado de

```js
for (var number = 1; number < 8; number = number * 3) {
  console.log(number);
}
```

#### Opções

1. 1
2. 1, 3, 9
3. 0, 1, 3, 9
4. 1, 3

<solution style="display:none;">4</solution>

### 8) Ao seguinte switch faltam alguns "breaks". Qual seria o resultado de executar o código assim como está?

```js
var weather = 'ensolarado';

switch (weather) {
  case 'lluvioso':
    console.log('Lembre de levar um guarda-chuvas.');
    break;
  case 'soleado':
    console.log('Use roupas leves.');
  case 'nublado':
    console.log('Saia para a rua.');

  default:
    console.log('Tipo de clima desconhecido');
    break;
}
```

#### Opções

1. Imprime 'Saia para a rua.'
2. Imprime 'Tipo de Clima desconhecido.'
3. Imprime 'Saia para a rua.'" e 'Tipo de Clima desconocido.'
4. Imprime 'Use roupas leves.', 'Saia para a rua.' e 'Tipo de Clima desconhecido.'

<solution style="display:none;">4</solution>

### 9) Qual o resultado de

```js
for (var i = 0; i <= 10; i++) {
  if (i == 0) {
    continue;
  } else {
    console.log(i);
  }
}
```

#### e logo imprime o 

1. Imprime os números inteiros do 0 ao 10 (inclusive)
2. Imprime os números inteiros do 1 ao 10 (inclusive)
3. Imprime os números inteiros do 0 ao 10 (inclusive) e logo imprime o número
   0 denovo
4. Imprime os números inteiros do 1 ao 10 (inclusive) e logo imprime o número
   0 denovo

<solution style="display:none;">2</solution>

### 10) Qual o resultado de

```js
var medalForScore = function(score) {
  if (score < 3){
    return 'Bronze';
  }
  if (score < 7){
    return 'silver';
  }
  return 'Gold';
}

console.log(medalForScore(3));
```

#### Opções

1. Bronze
2. Silver
3. Gold
4. undefined

<solution style="display:none;">2</solution>

### 11) Uma função pode retornar múltiplos valores ao mesmo tempo

#### Opções

1. Verdadeiro
2. Falso

<solution style="display:none;">2</solution>

### 12) Os comandos como alert(), prompt() e console.log() são de fato funções

#### Opções

1. Verdadeiro
2. Falso

<solution style="display:none;">1</solution>
