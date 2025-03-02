#### Desafio: hora da prática

1) Pergunte ao usuário qual é o dia da semana. Se a resposta for "Sábado" ou "Domingo", mostre "Bom fim de semana!". Caso contrário, mostre "Boa semana!".

```js
diaDaSemana = prompt('Qual é o dia da semana?');
if (diaDaSemana == 'Sábado') {
    alert('Bom fim de semana!');
} else if (diaDaSemana == 'Domingo') {
    alert('Bom fim de semana!');
} else {
    alert('Boa semana!');
}
```

2) Verifique se um número digitado pelo usuário é positivo ou negativo. Mostre um alerta informando.

```js
numero = prompt('Digite um número positivo ou negativo');
if (numero > 0) {
    alert('Número positivo!');
} else {
    alert('Número negativo!');
}
```

3) Crie um sistema de pontuação para um jogo. Se a pontuação for maior ou igual a 100, mostre "Parabéns, você venceu!" no console do navegador. Caso contrário, mostre "Tente novamente para ganhar.".

```js
let ponto = prompt('Qual a sua pontuação?');
if(ponto >=100){
    alert('Parabéns, você venceu!');
}else{
    alert('Tente novamente para ganhar.')
}
```

4) Crie uma mensagem que informa o usuário sobre o saldo da conta, usando uma template string para incluir o valor do saldo.

```js
let saldoDaConta = prompt('Digite o saldo da conta.');
alert(`Saldo é de R$${saldoDaConta}`);
```

5) Peça ao usuário para inserir seu nome usando prompt. Em seguida, mostre um alerta de boas-vindas usando esse nome.

```js
let nome = prompt('Qual seu nome?');
    alert(`Boas vindas:  ${nome}`);
```


## Documentação
Alguns links úteis para a documentação oficial do JavaScript incluem:ara saber mais: ponto e vírgula no JavaScript:


- 💹 **Leitura complementar da documentação sobre o JavaScript.** — [Leitura complementar da documentação sobre o JavaScript.](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Lexical_grammar#automatic_semicolon_insertion)
- 💹 **Quer saber o que a comunidade recomenda? Leia mais neste link do Stack Overflow.** — [Quer saber o que a comunidade recomenda? Leia mais neste link do Stack Overflow.](https://www.alura.com.br/artigos/javascript)