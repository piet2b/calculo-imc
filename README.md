# Praticando com Variáveis, Operadores e Estruturas Condicionais. 
## Exercício: Calcular o imc de alguém

```ruby
const peso = A;
const alturaEmMetros = B;

const imc = peso / Math.pow(alturaEmMetros,2);
console.log(imc.toFixed(1));

if(imc < 18.5){
  console.log('abaixo do peso');
} else if (imc >= 18.5 && imc < 25){
  console.log('peso normal');
} else if (imc >= 25 && imc < 30){
  console.log('acima do peso');
} else if (imc >= 30 && imc < 40){
  console.log('obeso tipo 1');
} else {
console.log('obeso tipo 2');
}
```
