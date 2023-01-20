# calculadora.js

// Função 1: função tradicional sem parâmetros
function minhaFuncao1() {
    console.log("Essa é uma função tradicional sem parâmetros.");
}

// Função 2: função tradicional com parâmetros e retorno
function minhaFuncao2(num1, num2) {
    return num1 + num2;
}

// Função 3: arrow function com parâmetros e retorno
let minhaFuncao3 = (num1, num2) => {
    return num1 * num2;
}

// Usando as funções em um programa de calculadora
let num1 = 5;
let num2 = 10;
minhaFuncao1();
console.log("A soma é: " + minhaFuncao2(num1, num2));
console.log("A multiplicação é: " + minhaFuncao3(num1, num2));
