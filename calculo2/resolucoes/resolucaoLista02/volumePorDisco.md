# Cálculo do Volume - Método do Disco

---
## Sólidos de Revolução
Um sólido gerado pela rotação de uma curva em torno de um eixo é chamado de Sólido de Revolução.

A seção transversal que corta um sólido de revolução será **sempre** um disco.<br>
Essa é a vantagem de usar esses sólidos, a seção transversal é conhecida.

A área de um disco é calculada da mesma forma que a **circunferência**: πr²

---
## Passo a Passo
1. Desenhar o Plano Cartesiano e a curva dada no enunciado;<br>
2. Saber se a rotação é em torno do eixo X, Y, de uma reta horizontal ou vertical;<br>
3. Determinar o Raio do Disco;<br>
4. Identificar os Limites de Integração;<br>
5. Montar a Integral.<br>

> Caso o sólido seja rotacionado em torno do eixo X, o raio do disco será a própria função rotacionada, no formato r(x);<br>
> Caso o sólido seja rotacionado em torno do eixo Y, o raio do disco será a própria função rotacionada, no formato r(y);<br>
> Caso o sólido seja rotacionado em torno de uma reta L vertical, o raio do disco será: L - r(y);<br>
> Caso o sólido seja ratocacionado em torno de uma rela L horizontal, o raio do disco será: r(x) - L;<br>

> Se o sólido for girado em torno de um eixo vertical (Y ou uma reta L qualquer), os limites de integração estarão na vertical;<br>
> Se o sólido for girado em torno de um eixo horizontal (X ou uma reta L qualquer), os limites de integração estarão na horizontal;<br>

> Não é preciso desenhar o sólido em si, mas sim desenhar o gráfico com a curva e os limites de integração.

---
## Exemplo - Curva rotacionada em torno do eixo X

> A região entre a curva y = √x, de x = 0 até x = 4, é girada em torno do eixo x, gerando um sólido.<br>
> Determine a integral que calcula o volume deste sólido.

Primeiramente, monte o gráfico.<br>
![img01](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/graficoQuestao01.png)

Como a função foi girada em torno do eixo X = 0, então o raio será a própria função √x.<br>
A área do disco será π * (√x)².<br>
Os limites de integração estão bem definidos, x = 0 até x = 4.

Logo, a integral que calcula o volume do sólido acima é:<br>
![img02](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/integralQuestao01Disco.png)

---
## Exemplo - Curva rotacionada em torno do eixo Y

> Determine a integral que calcula o volume do seguinte sólido:<br>
> Sólido obtido com a rotação, em torno do eixo y, da região compreendida entre Y = 1 e Y = 4, e a curva X = 2/Y.

Observe que desta vez, a rotação é em torno do eixo Y. Neste caso, o raio do disco deve ser em função de Y.<br>
A questão já nos deu a função em torno de Y.

Assim, identificamos o raio:<br>
O raio será a função (curva) que foi rotacionada. 
Porém, lembre que a função deve estar em função de Y, algo que já nos foi dado no enunciado.<br>
Assim, o raio é 2/Y.

O limite de integração é Y = 1 e Y = 4.

Assim, temos o seguinte gráfico e a seguinte integral:

![img05](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/GraficoDesafio03.png)
![img06](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/IntegralDesafio03.png)

---
## Exemplo - Curva rotacionada em torno de uma reta vertical

> Parábola X = Y² + 1 rotacionada em torno da reta X = 3. Determine a integral que calcula o vólume do sólido.

Neste caso, temos uma reta vertical X = 3.<br>
Já que a rotação é em torno de uma reta vertical, a função deve estar em razão do y.<br>
Quando a rotação é em torno de uma reta vertical, o valor da reta (no caso, X = 3), deve ser subtraído pela função dada.<br>
Fazendo isso, teremos o raio do disco.

Assim, temos que o raio deste exemplo é: **3 - (Y² + 1)**

Observe que a função dada já está em razão do Y, logo só foi preciso realizar a subtração do valor da reta vertical.

Para encontrar os limites de integração, como não foi nos dado no enunciado, basta fazer o seguinte:<br>
Substitua na função dada (X = Y² + 1), o valor da reta vertical (X = 3).<br>
3 = Y² + 1<br>
Y = +√2 ou -√2

Portanto, temos a seguinte integral:<br>
![img07](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/00000000000000000000.png)

---
## Exemplo - Curva rotacionada em torno de uma reta horizontal

> Determine a integral que calcula o volume do sólido obtido com a rotação da curva y = √x, em torno da reta y = 1 e x = 4.

Observe que, dessa vez, a rotação é em torno da reta horizontal Y = 1.<br>
Sabendo que a função dada é √x, qual o valor de X para Y ser 1?<br> É 1, pois √1 = 1.<br>

Desse modo, temos o seguinte gráfico:<br>
![img03](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/graficoQuestao02.png)

O raio do disco será a própria função, subtraída de 1 unidade, pois o sólido começa a girar em X = 1.<br>
Logo, o raio será √x - 1<br>
Assim, a área do disco será dada por: π * (√x - 1)²

Os limites de integração serão: x = 1 e x = 4.<br>
Logo, a integral que calcula o volume do sólido é:<br>
![img04](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/00.png)

