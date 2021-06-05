# PAD2-atividade-de-fixa-o






// 2 – Crie uma função que dado dois valores e uma Callback (passados como parâmetros), mostre no console a soma, subtração, multiplicação e divisão desses valores, dependendo da função Callback.

function soma(x, y) {
    return x + y;
}

function subtracao(x, y) {
    return x - y;
}

function multiplicacao(x, y) {
    return x * y;
}

function divisao(x, y) {
    return x / y;
}

function calculadora(x, y, callback) {
    console.log(callback(x, y));
}
