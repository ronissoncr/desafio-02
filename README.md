# Desafio Prático de JavaScript: Depuração e Boas Práticas

## Objetivo

Aprender a depurar (debug) código JavaScript utilizando ferramentas práticas e aplicar boas práticas de desenvolvimento.

## Atividade

### Parte 1 - Código com Erros

Dado o código abaixo, identifique e corrija os erros utilizando ferramentas de depuração:

```javascript
function calcularMedia(notas) {
  let soma = 0;
  for (let i = 0; i <= notas.length; i++) {
    soma += notas[i];
  }
  return soma / notas.length;
}

let notas = [8, 9, 7];
console.log("Média das notas é: " + calcularMedia(notas));
```

### Passos para resolver:

1. Identifique e corrija os erros no código acima.
2. Use ferramentas de depuração web, como o console do navegador (Chrome DevTools).

## Ferramenta recomendada

- Utilize o Console do Navegador (Chrome DevTools) para realizar o debug do código em tempo real.
- ou https://playcode.io/javascript 

## Entrega

Corrija o código acima e entregue um arquivo JavaScript corrigido, explicando no próprio arquivo quais eram os erros e como foram corrigidos.

## Avaliação

- Clareza na identificação e explicação dos erros.
- Eficiência na utilização da ferramenta de depuração.
- Aplicação correta das boas práticas aprendidas.

