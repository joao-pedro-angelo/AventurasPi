# Integração Trigonométrica

> Recomendo a leitura do seguinte material: [Integrais Trigonométricas](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/integrais/pdfs/integracaoProdutoPotencia.pdf)

> Sumário:
> 1. Potências de Senos
> 2. Potências de Cossenos
> 3. Produto de Funções Trigonométricas
> 4. Seno(mx) * Cosseno(nx)
> 5. Secante e Tangente

---
## Integrais com Potências de Senos

> Vídeo: https://youtu.be/FtJGJmKTkrI

#### Seno elevado a um inteiro par

Para o seno elevado a um inteiro par, basta usar a relação abaixo:<br>
**seno²x = (1 - cos2x) / 2**

#### Seno elevado a um inteiro ímpar

Para o seno elevado a um inteiro ímpar, use a propriedade de multiplicação de potências de mesma base.<br>
Com essa propriedade, você obtém um seno elevado a um inteiro par e outro elevado a 1.<br>
O seno que está elevado ao inteiro par, você vai substituir pela relação fundamental trigonométrica.<br>
Agora, basta usar substituição simples, o seno que ficou sobrando fará parte do du.

![img02](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/seno02.png)

---
## Integrais com Potências de Cossenos

> Vídeo: https://youtu.be/FtJGJmKTkrI<br>

#### Cosseno elevado a um inteiro par

Para o cosseno elevado a um inteiro par, basta usar a relação abaixo:<br>
**cos²x = (1 + cos2x)/2**

![img01](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/cosseno01.png)<br>

#### Cosseno elevado a um inteiro ímpar

Para o cosseno elevado a um inteiro ímpar, use a propriedade de multiplicação de potências de mesma base.<br>
Com essa propriedade, você obtém um cosseno elevado a um inteiro par e outro elevado a 1.<br>
O cosseno que está elevado ao inteiro par, você vai substituir pela relação fundamental trigonométrica.<br>
Agora, basta usar substituição simples, o cosseno que ficou sobrando fará parte do *du*.

![img03](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/cosseno03.png)<br>
![img04](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/cosseno04.png)<br>
![img05](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/cosseno05.png)<br>
![img06](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/cosseno06.png)<br>

---
## Produto de Funções Trigonométricas

Para integrais do tipo sen^n * cosseno^m, observe os expoentes de ambas as funções trigonométricas.<br>
Caso ambos forem pares, use alguma das relações abaixo:

**cos²x = (1 + cos2x)/2**<br>
**sen²x = (1 - cos2x)/2**<br>

Caso ao menos um dos expoentes for um inteiro ímpar, separe a função cujo expoente é impar em um produto de mesma base.<br>
Exemplo: sen⁵x = sen⁴x * sen x<br>
A parte com expoente ímpar será usada para compor o *du* na substituição simples.<br>
A parte com expoente par deve ser substituída pela relação fundamental trigonométrica, que está abaixo.

**sen²x + cos²x = 1**

Após usar esta relação, faça a distributiva e utilize a integração por substituição simples.
O *u* será a função que você não separou em um produto de mesma base. No exemplo acima, separamos o seno.<br>
Então o *u* seria o cosseno. 

---
## Seno(Mx) * Cosseno(Nx)

#### Integral do tipo - Sen(Mx) * Cos(Nx)

![img01](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/integralEspecial01.png)

#### Integral do tipo - Sen(Mx) * Sen(Nx)

![img02](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/integralEspecial02.png)

#### Integral do tipo Cos(Mx) * Cos(Nx)

![img03](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/integralEspecial03.png)

---
## Secante e Tangente

A principal relação para o cálculo de integrais envolvendo secante e tangente é:<br>
**tg²x + 1 = sec²x**

Com a relação acima, é possível resolver qualquer integral que envolva tangente e secante.

Lembre que a derivada da tangente é *secante ao quadrado*.<br>
A derivada da secante é *secante * tangente*.

Além disso, saiba que a tangente é a divisão entre o seno e cosseno (seno/cosseno).<br>
A secante é o inverso do cosseno (1/cosseno).
