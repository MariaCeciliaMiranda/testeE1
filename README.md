# testeE1
Crie uma função que recebe dois argumentos string e retorna o de maior comprimento.

 var arr = [1, 2];
var max = arr.reduce(function(a, b) {
  return Math.max(a, b);
}, -Infinity);

function getMaxOfArray(numArray) {
    return Math.max.apply(null, numArray);
}
