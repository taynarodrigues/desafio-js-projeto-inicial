#### Desafios - Números aleatórios

A função Math.random em JavaScript gera um número decimal aleatório entre 0 (inclusivo) e 1 (exclusivo) de forma pseudo aleatória. Isso significa que os números gerados podem estar em qualquer lugar entre 0 (inclusive) e quase 1 (exclusivo), com uma precisão de até 16 casas decimais. A função Math.random usa um valor interno inicial que é geralmente baseado no horário atual do sistema, gerando números pseudo aleatórios.

```js

Para gerar um número entre 1 e 3, podemos usar o código: let numeroAleatorio1a3 = parseInt(Math.random() * 3) + 1;

O código acima gera um número aleatório inteiro entre 1 e 3, ambos inclusivos. Portanto, os números possíveis que podem ser gerados por esse código são: 1, 2 e 3.


```

#### Desafios - Operador ternário

```js

Usamos o operador ternário para definir o valor da variável palavraPessoa. Se quantidadePessoas for igual a 1, palavraPessoa recebe o valor "pessoa", caso contrário, recebe o valor "pessoas".

let palavraPessoa = quantidadePessoas == 1 ? 'pessoa' : 'pessoas';

```
