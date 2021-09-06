# 1. O Poder do Javascript

No caminho para se tornar um mestre `Backend` você deve estudar a linguagem de programação `Javascript` e ser capaz de resolver os problemas propostos a seguir. Para isso é preciso ter uma conta no site: <https://www.urionlinejudge.com.br/judge/pt>

## Usando o Judge

Na hora de resolver, escolha a linguagem JavaScript 12.18 (nodejs 12.18.3)

Por padrão o URI já vai te dar esse trecho de código:

```javascript
var input = require('fs').readFileSync('/dev/stdin', 'utf8');
var lines = input.split('\n');

/**
 * Escreva a sua solução aqui
 * Code your solution here
 * Escriba su solución aquí
 */
```

Cada linha de entrada ficará armazenada no array `lines` como uma `string`.
Caso o valor de entrada seja numérico é preciso converter em número usando a função `Number()`, exemplo:
```javascript
let a = Number(lines[0]);
```

Caso em uma mesma linha existam vários valores separados por espaço você deve separa-los da seguinte maneira:
```javascript
// ENTRADA: 35 99 107 22

const lineValues = lines[0].split(" ");


// lineValues[0] === "35"
// lineValues[1] === "99"
// lineValues[2] === "107"
// lineValues[3] === "22"
```

Caso você esteja confortável com destructuring, pode fazer

```javascript
// ENTRADA: 35 99 107 22

const [a, b, c, d] = lines[0].split(" ");

// a === "35"
// b === "99"
// c === "107"
// d === "22"
```

## Exercícios

### 1. Expressões aritméticas

* [Extremamente Básico](https://www.urionlinejudge.com.br/judge/pt/problems/view/1001)
* [Área do Círculo](https://www.urionlinejudge.com.br/judge/pt/problems/view/1002)
* [Soma Simples](https://www.urionlinejudge.com.br/judge/pt/problems/view/1003)
* [Produto Simples](https://www.urionlinejudge.com.br/judge/pt/problems/view/1004)
* [Média 1](https://www.urionlinejudge.com.br/judge/pt/problems/view/1005)
* [Média 2](https://www.urionlinejudge.com.br/judge/pt/problems/view/1006)
* [Diferença](https://www.urionlinejudge.com.br/judge/pt/problems/view/1007)
* [Salário](https://www.urionlinejudge.com.br/judge/pt/problems/view/1008)
* [Salário com Bônus](https://www.urionlinejudge.com.br/judge/pt/problems/view/1009)
* [Cálculo Simples](https://www.urionlinejudge.com.br/judge/pt/problems/view/1010)

### 2. Desvios condicionais

* [Fórmula de Bhaskara](https://www.urionlinejudge.com.br/judge/pt/problems/view/1036)
* [Intervalo](https://www.urionlinejudge.com.br/judge/pt/problems/view/1037)
* [Lanche](https://www.urionlinejudge.com.br/judge/pt/problems/view/1038)
* [Coordenadas de um Ponto](https://www.urionlinejudge.com.br/judge/pt/problems/view/1041)
* [Sort Simples](https://www.urionlinejudge.com.br/judge/pt/problems/view/1042)
* [Triângulo](https://www.urionlinejudge.com.br/judge/pt/problems/view/1043)
* [Múltiplos](https://www.urionlinejudge.com.br/judge/pt/problems/view/1044)
* [DDD](https://www.urionlinejudge.com.br/judge/pt/problems/view/1050)
* [Mês](https://www.urionlinejudge.com.br/judge/pt/problems/view/1052)
* [Numeração Romana para Números de Página](https://www.urionlinejudge.com.br/judge/pt/problems/view/1960)

### 3. Laços

* [Números Pares](https://www.urionlinejudge.com.br/judge/pt/problems/view/1059)
* [Positivos e Média](https://www.urionlinejudge.com.br/judge/pt/problems/view/1064)
* [Pares entre Cinco Números](https://www.urionlinejudge.com.br/judge/pt/problems/view/1065)
* [Sequência de Números e Soma](https://www.urionlinejudge.com.br/judge/pt/problems/view/1101)
* [Várias Notas Com Validação](https://www.urionlinejudge.com.br/judge/pt/problems/view/1118)
* [Resto da Divisão](https://www.urionlinejudge.com.br/judge/pt/problems/view/1133)
* [Fibonacci Fácil](https://www.urionlinejudge.com.br/judge/pt/problems/view/1151)
* [Fatorial Simples](https://www.urionlinejudge.com.br/judge/pt/problems/view/1153)
* [Idades](https://www.urionlinejudge.com.br/judge/pt/problems/view/1154)
* [Crescimento Populacional](https://www.urionlinejudge.com.br/judge/pt/problems/view/1160)

### 4. Vetores e Matrizes

* [Substituição em Vetor I](https://www.urionlinejudge.com.br/judge/pt/problems/view/1172)
* [Preenchimento de Vetor I](https://www.urionlinejudge.com.br/judge/pt/problems/view/1173)
* [Troca em Vetor I](https://www.urionlinejudge.com.br/judge/pt/problems/view/1175)
* [Preenchimento de Vetor II](https://www.urionlinejudge.com.br/judge/pt/problems/view/1177)
* [Menor e Posição](https://www.urionlinejudge.com.br/judge/pt/problems/view/1180)
* [Linha na Matriz](https://www.urionlinejudge.com.br/judge/pt/problems/view/1181)
* [Coluna na Matriz](https://www.urionlinejudge.com.br/judge/pt/problems/view/1182)
* [Acima da Diagonal Principal](https://www.urionlinejudge.com.br/judge/pt/problems/view/1183)
* [Abaixo da Diagonal Principal](https://www.urionlinejudge.com.br/judge/pt/problems/view/1184)
* [Área Direita](https://www.urionlinejudge.com.br/judge/pt/problems/view/1190)

### 5. Strings

TODO

### 6. Ordenação

* [Fila do Recreio](https://www.urionlinejudge.com.br/judge/pt/problems/view/1548)
* [Grid de Largada](https://www.urionlinejudge.com.br/judge/pt/problems/view/1228)
* [Pares e Ímpares](https://www.urionlinejudge.com.br/judge/pt/problems/view/1259)
* [Onde está o Mármore?](https://www.urionlinejudge.com.br/judge/pt/problems/view/1025)

### 7. Estruturas

* [Ida à Feira](https://www.urionlinejudge.com.br/judge/pt/problems/view/1281)
* [Ordenação por Tamanho](https://www.urionlinejudge.com.br/judge/pt/problems/view/1244)
* [Diga-me a Frequência](https://www.urionlinejudge.com.br/judge/pt/problems/view/1251)
* [Lista Telefônica Econômica](https://www.urionlinejudge.com.br/judge/pt/problems/view/1211)
* [Camisetas](https://www.urionlinejudge.com.br/judge/pt/problems/view/1258)

### 8. Pilhas e Filas

* [Trilhos](https://www.urionlinejudge.com.br/judge/pt/problems/view/1062)
* [Trilhos Novamente... Traçando Movimentos](https://www.urionlinejudge.com.br/judge/pt/problems/view/1063)
* [Balanço de Parênteses I](https://www.urionlinejudge.com.br/judge/pt/problems/view/1068)
* [Diamantes e Areia](https://www.urionlinejudge.com.br/judge/pt/problems/view/1069)
* [Jogando Cartas Fora](https://www.urionlinejudge.com.br/judge/pt/problems/view/1110)
* [Estacionamento Linear](https://www.urionlinejudge.com.br/judge/pt/problems/view/1523)

### 8. Recursão

TODO


## Material

### Vídeos

[EM CONSTRUÇÃO: ACEITO SUGESTÕES]

### Livros

* [Livro Iterativo - Eloquent Javascript](https://eloquentjavascript.net/index.html)

### Artigos

[EM CONSTRUÇÃO: ACEITO SUGESTÕES]
