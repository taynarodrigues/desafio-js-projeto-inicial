
#### Desafio: hora da prática

1) Contador 1 - Os loops permitem automatizar tarefas repetitivas e lidar com grandes quantidades de dados de forma eficiente.

```js
let contador = 1;

while (contador < 4) {
  console.log('Executando a iteração ' + contador);
  contador = contador + 1;
}

while (contador < 4){ } começa o loop while. Ele continuará repetindo o bloco de código entre as chaves { } enquanto a condição contador < 4 for verdadeira.
 Essa condição significa que o loop continuará enquanto o valor da variável contador for menor que 4.

O resultado final será a impressão das mensagens "Executando a iteração 1", "Executando a iteração 2" e "Executando a iteração 3" no console.
O loop foi executado três vezes, e o valor final da variável contador é 4. Na quarta iteração, o valor de contador é 4. Neste momento, a condição contador < 4 se torna falsa, pois 4 não é menor que 4. O loop não executa mais o código dentro das chaves e termina.

```

2) Crie um contador que comece em 1 e vá até 10 usando um loop while. Mostre cada número.

```js
    let cont =1;
    while(cont <= 10){
        alert('Executando a contagem ' + cont);
        cont++;
    }

```

3) Crie um contador que começa em 10 e vá até 0 usando um loop while. Mostre cada número.

```js
    let c =10;
    while(c >= 0){
        alert(c);
        c--;
    }
```

4) VCrie um programa de contagem regressiva. Peça um número e conte deste número até 0, usando um loop while no console do navegador.

```js
    let numeroMaximo = prompt("Digite um número para a contagem regresiva: ");
    while(numeroMaximo >=0){
    alert(numeroMaximo);
        numeroMaximo--;
    }
```


5) Crie um programa de contagem progressiva. Peça um número e conte de 0 até esse número, usando um loop while no console do navegador.

```js
    let numeroMax = prompt('Digite um número para a contagem progressiva;');
    while(numeroMax >=0){
        alert(numeroMax);
        numeroMax++;
    }
```

