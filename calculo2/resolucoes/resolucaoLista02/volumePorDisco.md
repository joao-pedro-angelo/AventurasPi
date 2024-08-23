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
2. Determinar o Raio do Disco;<br>
3. Identificar os Limites de Integração;<br>
4. Montar a Integral.<br>

> O raio do disco quase sempre será a função que foi rotacionada.<br>
> Porém, em alguns casos, pequenos ajustes devem ser feitos.<br>
> Esses casos normalmente ocorrem quando o giro da função não é em torno do eixo X = 0.<br>

> Não é preciso desenhar o sólido em si, mas sim desenhar o gráfico com a curva e os limites de integração.

---
## Exemplo 1

> A região entre a curva y = √x, de x = 0 até x = 4, é girada em torno do eixo x, gerando um sólido.<br>
> Determine a integral que calcula o volume deste sólido.

Primeiramente, monte o gráfico desde problema.<br>
![img01](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/graficoQuestao01.png)

Como a função foi girada em torno do eixo X = 0, então o raio será a própria função √x.<br>
A área do disco será π * (√x)².<br>
Os limites de integração estão bem definidos, x = 0 até x = 4.

Logo, a integral que calcula o volume do sólido acima é:<br>
![img02](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/integralQuestao01Disco.png)

---
## Exemplo 2

> Determine a integral que calcula o volume do sólido obtido com a rotação da curva y = √x, em torno da reta y = 1 e x = 4.

Observe que, dessa vez, a rotação é em torno da reta Y = 1, não em torno do eixo X.<br>
Sabendo que a função dada é √x, qual o valor de X para Y ser 1?<br> É 1, pois √1 = 1.<br>

Desse modo, temos o seguinte gráfico:<br>
![img03](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/graficoQuestao02.png)

O raio do disco será a própria função, subtraída de 1 unidade, pois o sólido começa a girar em X = 1, já que f(1) = 1.<br>
Assim, a área do disco será dada por: π * √(x - 1)²

Os limites de integração serão: x = 1 e x = 4.<br>
Logo, a integral que calcula o volume do sólido é:<br>
![img04](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/integralQuestao02Disco.png)
