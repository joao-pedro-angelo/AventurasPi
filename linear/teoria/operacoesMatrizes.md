# Operações com Matrizes

---
## Adição

Para que seja possível somar duas matrizes, é necessário primeiro que elas sejam do mesmo tipo, ou seja, que tenham o mesmo número de linhas e colunas. A adição é feita a partir da soma dos elementos que ocupam as mesmas posições.

![img01](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/matrizSoma.png)

---
## Subtração

Da mesma forma que a adição, na subtração basta subtrair os elementos que estão na mesma posição. Mas cuidado, a ordem em que você executa a operação irá mudar o sinal dos seus resultados, ou seja, sendo duas matrizes A e B, A – B é diferente de B – A.

![img02](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/matrizSubtracao.png)

---
## Produto entre Matrizes

Primeiro, para que seja possível realizarmos essa operação, temos que observar se o número de linhas da primeira matriz é igual ao número de colunas da segunda, pois esses valores serão a quantidade de linhas e colunas da matriz gerada pela multiplicação. Se isso acontecer, ótimo, podemos multiplicá-las, porém, se essa condição não for atendida, aí não podemos fazer essa operação.

Em uma multiplicação de matrizes, devemos multiplicar os elementos da linha da primeira matriz pelos elementos da coluna da segunda matriz e somar esses produtos. Por exemplo, se tivermos duas matrizes A3x2 e B2x3, multiplicamos o 1° elemento da linha 1 da matriz A pelo 1° elemento da coluna 1 da matriz B, somamos ao produto do 2° elemento da linha 1 da matriz A pelo 2° elemento da coluna 1 da matriz B e assim por diante.

![img03](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/matrizMultiplicacao.png)

---
## Multiplicação por Escalar

Multiplicar uma matriz por um número real qualquer é bem simples, basta pegar esse número e multiplicar por todos os elementos da matriz, gerando assim, uma nova matriz.

![img04](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/matrizMultiplicacaoPorUmInteiro.png)
