# Volume por Fatiamento

## Passo a Passo
1. Esboce o sólido e uma Seção Transversal que corte o sólido;
2. Encontre a fórmula da área da Seção Transversal;
3. Encontre os limites de integração;
4. Monte a integral.

---
### Macetes
#### 1. Cone
Sempre que tiver um cone, a seção transversal será um **círculo**. A área do círculo é `πR²`.

#### 2. Pirâmide de Base Quadrada ou Retangular
A seção transversal será sempre um **quadrado** (ou retângulo), e o lado do quadrado (ou os lados do retângulo) diminuem linearmente com a altura. 

#### 3. Esfera
A seção transversal em qualquer altura `z` será um **círculo**. O raio desse círculo é dado por `r(z) = sqrt(R^2 - z^2)`, onde `R` é o raio da esfera.

#### 4. Sólido de Revolução
Quando o sólido é obtido pela rotação de uma curva em torno de um eixo, a seção transversal perpendicular ao eixo de rotação é sempre um **círculo**. O raio desse círculo é dado pelo valor da função que foi rotacionada.

#### 5. Paraboloide
Se a função que gera o sólido é da forma `y = ax^2 + bx + c`, ao rotacioná-la em torno do eixo X, a seção transversal será um **círculo** com raio `r(x) = y = ax^2 + bx + c`.

#### 6. Semiesfera ou Casca Esférica
A seção transversal ao longo do eixo de simetria (geralmente o eixo Z) será um **círculo** com raio `r(z) = sqrt(R^2 - z^2)`. Este macete é útil tanto para calcular o volume de uma esfera inteira quanto de uma casca esférica.


---
### 1º Exemplo
> Encontre a integral que calcula o volume de uma pirámide de 3 metros de altura, com base quadrada de lado 3.<br>
> A pirâmide é cortada por uma seção transversal que é um quadrado de lado x.

Pelo enunciado, sabemos que a seção transversal é um quadrado de lado X. Logo, a fórmula da área dessa seção é X².<br>
Como a pirâmide tem 3 metros de altura, podemos desenhá-la no plano cartesiado do X = 0 até o X = 3.<br>
Sendo assim, os limites de integração são a = 0 e b = 3.<br>
![img01](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/220801.png)


Logo, a integral que resulta no volume desta pirâmide é: Integral de X² dx, a = 0 e b = 3.<br>
![img02](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/220802.png)

---
### 2º Exemplo
> O sólido está situado entre os planos perpendiculares X = 0 e X = 4.<br>
> As seções transversais que cortam este sólido são quadrado cujos lados se estendem de Y = -√x até Y = √x<br>
> Encontre a integral que resulta no volume deste sólido.

O esboço do sólido é o seguinte:<br>
![img03](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/220803.png)

As seções transversais são quadrados cujos lados são:<br>
Raiz de X - (- Raiz de X) = 2 Raiz de X<br>

Logo, a integral que calcula o volume do sólido acima é:<br>
2 * Integral de Raiz de X dx, a = 0 e b = 4<br>

---
### 3º Exemplo
> O sólido está entre os planos X = -1 e X = 1.<br>
> As Seções Transversais que cortam este sólido têm diametros que vão de Y = X² até Y = 2 - X².

Esboce o sólido: <br>
![img03](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/220804.png)

O que foi feito acima?<br>
Foi desenhada a curva Y = X² e a curva Y = 2 - X².<br>
As curvas se intesectam nos pontos X = -1 e X = 1.<br>

Como a curva Y = 2 - X² é quem está no topo, o diâmetro da seção transversal é dado por:<br>
D = (2 - X²) - (X²) = 2 - 2X²<br>

Logo, o raio da seção transversal é 1 - X².<br>
Sendo assim, a área da seção transversal é dada por πR² = π(1 - x²)²<br>

Portanto, a fórmula que calcula o volume do sólido acima é:<br>
π * Integral de (1 - x²)² dx, a = -1 e b = 1

---
### 4º Exemplo
> O sólido está situado no plano carteasiano entre X = -1 e X = 1.<br>
> As seções transversais são quadrados cujas bases se estendes do semi-círculo Y = Raiz de -(1 - x²) até Y = (1 - x²).<br>

Esboço do sólido: <br>
![img04](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/220805.png)

O que foi feito acima?<br>
Foi desenhado ambos os semi-círculos, formando uma circunferência situada entre X = -1 e X = 1.<br>
Em seguida, foi encontrado o lado do quadrado que corta a circunferência.<br>

Agora, sabendo que a área do quadrado é dada por lado², temos que:<br>
Área do quadrado que fatia a circunferência acima é dada por: (2 * raiz de [1 - x²])²<br>

Sendo assim, a integral que calcula o volume do sólido deste exemplo é:<br>
Integral de (2 * raiz de [1 - x²])² dx, a = -1 e b = 1<br>
4 * Integral de (raiz de [1 - x²])² dx, a = -1 e b = 1<br>

---
### 5º Exemplo
> O sólido está situado no plano carteasiano entre X = -1 e X = 1.<br>
> As seções transversais são quadrados cujas diagonais se estendem do semi-círculo Y = Raiz de -(1 - x²) até Y = (1 - x²).<br>

Observe que é quase o mesmo problema do 4º exemplo.<br>
Porém, agora o problema nos diz que as diagonais dos quadrados que se estendem no plano, não os lados.<br>
Assim, precisamos saber que Diagonal² = 2 * Lado².

Logo, o valor de (2 * raiz de [1 - x²]), que antes era o lado do quadrado, agora é a diagonal do mesmo.<br>

Sabendo disso, você terá condições de resolver o problema 5.

---
