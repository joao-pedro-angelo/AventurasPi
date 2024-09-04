# Resolução Prova 2º Estágio - 2024.1

---
## 1º a) Provar que é subespaço

> Para que um conjunto seja um subespaco, ele precisa satisfazer tres propriedades: conter o vetor nulo, ser fechado para adicao e ser fechado para multiplicacao escalar.

**1. Vetor Nulo:**
  (0, 0, 0) está presente em W, pois z = x*y e 0 = 0*0
  
**2. Fechamento Sob Adição:**
  - Sendo (x, y, z) e (a, b, c) elementos de W, temos:<br>
    - (x, y, z) = (x, y, xy)<br>
    - (a, b, c) = (a, b, ab)<br>
    - (x, y, xy) + (a, b, ab) = (x + a, y + b, xy + ab)<br>
    - Observe que xy + ab é diferente de (x + a) * (y + b). Logo, o fechamento aditivo não foi respeitado.<br>

**Conclusão:** W não é subespaço.

---
## 1ª b) Provar que é uma base

> Uma base é um conjunto Linearmente Independente que gera o espaço vetorial.<br>
> Sabemos que a dimensão de Pn é (n+1). Assim, a dimensão de P2 = 3.<br>
> Desse modo, como o conjunto apresentado tem 3 elementos, basta provarmos que é um conjunto LI.<br>

**1. Provar a Lineariedade:**
  - a(1 + t) + b(2t - t²) + c*3t² = 0
  - a + at + b2t - bt² + c3t²
  - (c - b)t² + (a + 2b)t + a = 0

**2. Resolver o sistema:**
  - a = 0
  - a + 2b = 0
  - c - b = 0

  Resolvendo este sistema, iremos encontrar a = 0, b = 0 e c = 0. Logo, o conjunto é LI.

  **Conclusão:** O conjunto apresentado é uma base de P2.

---
## 2ª a) Dimensão de um Subespaço

**1. Reescrever a Matriz dada como uma combinação linear:**
  - a[1 0];[1 0]  + b[1 -1];[0  0] + c[0 2];[2 0]

> O ponto e vírgula (;) separa as linhas das matrizes. É uma limitação do Markdown.

  - Agora, temos que as 3 matrizes acima formam um conjunto gerador do subespaço dado.<br>
  - Para que este conjunto seja uma base, é preciso que além de gerador, ele seja LI.<br>
  - Provar a Lineariedade do conjunto acima é simples.<br>
  - Basta observar a posição dos zeros nas matrizes.<br>
  - Nenhuma das matrizes encontradas pode ser escrita como combinação linear das outras duas.<br>
  - Logo, o conjunto formado por essas 3 matrizes é uma base de U.<br>
  - Assim, dim(U) = 3.

---
## 2ª b) Combinação Linear

(-1, k, -7) = a(1, -3, 2) + b(2, 4, -1)<br>
(-1, k, -7) = (a, -3a, 2a) + (2b, 4b, -1b)<br>
(-1, k, -7) = (a + 2b, -3a + 4b, 2a - 1b)<br>

Temos o sistema:

- a + 2b = -1
- -3a + 4b = k
- 2a - 1b = -7

O valor de K será 13.

---
## 2ª c) Completar Base

Como o espaço R³ tem dimensão igual a 3, a base tem que ter 3 elementos.<br>
Basta escolher um vetor que não possa ser escrito como combinação linear de W1 e W2.<br>

Use o número zero para isso.

Assim, escolha um vetor do tipo: (0, 0, X), com X != 0.

O vetor que eu escolhi foi: (0, 0, 10).

O Conjunto {(1, -1, 0), (2, -1, 0), (0, 0, 10)} é uma base.

---
## 2ª d) Encontrar Base de um Subespaço

Sendo (x, y, z) um elemento qualquer de W1, temos:<br>
(x, y, z) = (x, y, 2x + y)

Reescrevendo como combinação linear de 'x' e 'y':<br>
(x, y, 2x + y) = x(1, 0, 2) + y(0, 1, 1)

Assim, o conjunto {(1, 0, 2), (0, 1, 1)} é gerador de W1. Para ser uma base, basta ser LI.

Observe a posição dos zeros nos dois vetores do conjunto. Estes vetores não são múltiplos entre si, logo são LI.

Assim, o conjunto {(1, 0, 2), (0, 1, 1)} é uma base de W1.

---
## 3ª Interseção de Subespaços

Para que um elemento pertença a W1 e a W2, é preciso que ele satisfaça as seguintes condições:

- (x, y, z) / z = 2x + y<br>
- (a, a, 4a) / a é um real qualquer

Sendo **x = a**, **y = a** e **z = 4a**, temos:

4a = 2a + a<br>
4a = 3a<br>
4a - 3a = 0<br>
a = 0

Assim, para que um elemento satisfaça as duas condições, é preciso que a = 0.

Então, temos:<br>
(a, a, 4a) = (0, 0, 0)

Logo, o único elemento que faz parte da interseção entre W1 e W2 é: (0, 0, 0)

**Conclusão:** Interseção entre W1 e W2 é apenas o vetor nulo, {(0, 0, 0)}

---
## 3ª Dimensão da União de Subespaços

Agora, para encontrar a dimensão de W1 + W2, é preciso conhecer a seguinte fórmula:

**dim(W1 + W2) = dim(W1) + dim(W2) - dim(interseção W1 e W2)**

Já vimos que a interseção entre W1 e W2 é apenas o vetor nulo, logo a dimensão é 0.

> Encontrando base para W1<br>
Para encontrar a dimensão de W1, basta encontrar uma base para este subespaço.

Sendo (x, y, z) um elemento qualquer de W1, temos:<br>
(x, y, z) = (x, y, 2x + y) = x(1, 0, 2) + y(0, 1, 1)

Como (1, 0, 2) e (0, 1, 1) não são múltiplos entre si, então formam uma base de W1. Logo, a dimensão de W1 é 2.

> Encontrando base para W2<br>
Sendo (a, a, 4a) um elemento qualquer de W2, temos:<br>
(a, a, 4a) = a(1, 1, 4)

Logo, {(1, 1, 4)} é uma base de W2. Assim, dim(W2) = 1.

Logo, dim(W1 + W2) = 2 + 1 - 0 = 3.

---
## 4ª Matriz de Mudança de Base

**1. Entender as bases e as coordenadas**
> Temos duas bases no espaço vetorial V de dimensão 3:
  - A base β = {v1, v2, v3}
  - A base 𝛾 = {𝑤1, 𝑤2, 𝑤3}

**2. Interpretar a matriz de mudança de base**

> Observação: O GPT interpretou a matriz de mudança de base de forma invertida.<br>
> Veja que a questão da uma matriz de mudança de base de Beta para Gama.<br>
> A IA interpretou como sendo uma matriz de Gama para Beta.<br>
> Porém, a lógica segue a mesma. O importante é entender o processo.

> Na questão, para encontrar [u1] (que está em base Beta) na sua versão em base Gama, basta multiplicar [u1] pela matriz dada.<br>
> A inversão será para encontrar [u2].

![img01](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/40901.png)

![img02](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/40902.png)

![img03](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/40903.png)

![img04](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/40904.png)

![img05](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/40905.png)

![img06](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/40906.png)

![img07](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/40907.png)
