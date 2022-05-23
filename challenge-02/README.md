# Desafio da semana #2

Nesse exercício, você está livre para escolher os nomes para suas variáveis e funções! :smile:

```js
// Crie uma função que receba dois argumentos e retorne a soma dos mesmos.
fuction soma(n1, n2) {
    return n1 + n2
}

// Declare uma variável que receba a invocação da função criada acima, passando dois números quaisquer por argumento, e somando `5` ao resultado retornado da função.
var resutx = resuty(3, 2) + 5;

// Qual o valor atualizado dessa variável?
10;
resutx = resutx;

// Declare uma nova variável, sem valor.
var novaVariavel;

/*
Crie uma função que adicione um valor à variável criada acima, e retorne a string:
    O valor da variável agora é VALOR.
Onde VALOR é o novo valor da variável.
*/
function valor() {
    novaVariavel = 3301;
    mensagem = 'O valor da variável agora é ' +novaVariavel;
}

// Invoque a função criada acima.
valor();

// Qual o retorno da função? (Use comentários de bloco).
?O valor da variável agora é 3301;

/*
Crie uma função com as seguintes características:
1. A função deve receber 3 argumentos;
2. Se qualquer um dos três argumentos não estiverem preenchidos, a função deve retornar a string:
    Preencha todos os valores corretamente!
3. O retorno da função deve ser a multiplicação dos 3 argumentos, somando `2` ao resultado da multiplicação.
*/
function multiplicacao(x, y, z) {
    if(x == undefined || y == undefined || z == undefined) {
        return 'Preencha todos os valores corretamente!';
    }
    return (x * y * z) + 2;
}

// Invoque a função criada acima, passando só dois números como argumento.
multiplicacao(2, 5);

// Qual o resultado da invocação acima? (Use comentários para mostrar o valor retornado).
?12

// Agora invoque novamente a função criada acima, mas passando todos os três argumentos necessários.
multiplicacao(2, 5, 10);

// Qual o resultado da invocação acima? (Use comentários para mostrar o valor retornado).
?102

/*
Crie uma função com as seguintes características:
1. A função deve receber 3 argumentos.
2. Se somente um argumento for passado, retorne o valor do argumento.
3. Se dois argumentos forem passados, retorne a soma dos dois argumentos.
4. Se todos os argumentos forem passados, retorne a soma do primeiro com o segundo, e o resultado, dividido pelo terceiro.
5. Se nenhum argumento for passado, retorne o valor booleano `false`.
6. E ainda, se nenhuma das condições acima forem atendidas, retorne `null`.
*/
function condicao(v1, v2, v3) {
    if(v1 != undefined) {
        return v1;
    }
    else if(v1 != undefined && v2 != undefined) {
        return v1 + v2;
    }
    else if(v1 != undefined && v2 != undefined && v3 != undefined) {
        return (v1 + v2) / v3
    }
    else if(v1 == undefined && v2 == undefined && v3 == undefined) {
        return false;
    }
    else {
        return null;
    }
}

// Invoque a função acima utilizando todas as possibilidades (com nenhum argumento, com um, com dois e com três.) Coloque um comentário de linha ao lado da         função com o resultado de cada invocação.
condicao(2);                //2
condicao(2, 4);             //6
condicao(2, 4, 2);          //3
condicao(v1, v2, v3);       //false
```