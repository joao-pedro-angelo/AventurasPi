# Resolução da Lista 4 - Espaço Vetorial

---
## Questão 1

**Quais dos conjuntos abaixo são subespaços vetoriais de R³? Justifique.**

**(a) W = {(x, y, z) em R³ | x - 3z = 0}**

**(b) W = {(x, y, z) em R³ | x em Z}**

**(c) W = {(x, y, z) em R³ | x >= 0}**

### Resolução:

Para ser um subespaço vetorial, um conjunto deve satisfazer três condições:
> 1. Deve conter o vetor nulo.<br>
> 2. Deve ser fechado sob adição.<br>
> 3. Deve ser fechado sob multiplicação escalar.<br>

**(a) W = {(x, y, z) em R³ | x - 3z = 0}**

Este conjunto contém todos os vetores de R³ que satisfazem a equação x - 3z = 0. Podemos reescrever como x = 3z. Qualquer adição de dois vetores em W também satisfará esta equação, assim como a multiplicação por um escalar. Portanto, W é um subespaço de R³.

**(b) W = {(x, y, z) em R³ | x em Z}**

Este conjunto inclui vetores em que a primeira coordenada x é um número inteiro. No entanto, a multiplicação de um vetor em W por um escalar real não garante que x continue sendo um número inteiro. Por exemplo, se multiplicarmos (1, 0, 0) por 0.5, obteremos (0.5, 0, 0), que não pertence a W. Portanto, W não é um subespaço vetorial.

**(c) W = {(x, y, z) em R³ | x >= 0}**

Este conjunto não é fechado sob multiplicação escalar. Por exemplo, se considerarmos o vetor (1, 0, 0) em W e o multiplicarmos por -1, obteremos (-1, 0, 0), que não está em W porque a primeira coordenada é negativa. Portanto, W não é um subespaço vetorial.

**Conclusão da Questão 1:** Apenas o conjunto (a) é um subespaço vetorial de R³.

---
## Questão 2

**Quais dos conjuntos abaixo são subespaços vetoriais de M(2, 2)? Justifique.**

**(a) W = {[a b; c d] em M(2, 2) | a = c e b + d = 0}**

**(b) W = {[a b; c d] em M(2, 2) | a + d <= b + c}**

**(c) W = {A em M(2, 2) | A = A^T}**

### Resolução:

**(a) Para verificar se o conjunto dado é um subespaço, precisamos checar as três condições mencionadas anteriormente.**

- Contém o vetor nulo: Se a = c = 0 e b + d = 0, então temos a matriz nula.
- Fechamento sob adição: Se A1 = [a1 b1; a1 d1] e A2 = [a2 b2; a2 d2] estão em W, então a1 + a2 = c1 + c2 e (b1 + b2) + (d1 + d2) = 0. Portanto, A1 + A2 está em W.
- Fechamento sob multiplicação escalar: Para um escalar k e uma matriz A = [a b; a d] em W, kA = [ka kb; ka kd], e como ka = kc e kb + kd = k(b + d) = 0, kA também está em W.

Portanto, o conjunto (a) é um subespaço de M(2,2).

**(b)** Este conjunto não é um subespaço vetorial porque a condição a + d <= b + c não é fechada sob adição ou multiplicação escalar.

> Geralmente, quando uma das condições de existência do conjunto é uma inequação, então este conjunto não será subespaço.<br>
> Pois a inequação, quando multiplicada por um escalar real negativo, terá seu sinal invertido.

**(c)** O conjunto de todas as matrizes simétricas (onde A = A^T) é um subespaço de M(2, 2). Para duas matrizes A, B em W, temos que A + B é simétrica e kA é simétrica para qualquer escalar k.

**Conclusão da Questão 2:** Apenas os conjuntos (a) e (c) são subespaços vetoriais de M(2, 2).

---
## Questão 3

**Quais dos conjuntos abaixo são subespaços vetoriais de P2? Justifique.**

> P2 é o conjunto formado por todos os polinômios de grau igual ou menor que 2.

**(a) W = {p(t) em P2 | p(0) = 0}**

**(b) W = {p(t) em P2 | p(0) = 2p(1)}**

**(c) W = {p(t) em P2 | p(t) + p'(t) = 0}**

### Resolução:

**(a) W = {p(t) em P2 | p(0) = 0}**

Este conjunto consiste de todos os polinômios de grau no máximo 2 que passam pela origem (0,0). Isto é um subespaço porque a soma de dois polinômios que satisfazem p(0) = 0 também satisfaz essa condição, e a multiplicação por um escalar também não altera o fato de que p(0) = 0.

**(b) W = {p(t) em P2 | p(0) = 2p(1)}**

Este conjunto é um subespaço vetorial, pois a condição p(0) = 2p(1) é preservada pela adição ou multiplicação por escalar.

**(c) W = {p(t) em P2 | p(t) + p'(t) = 0}**

Este conjunto é um subespaço, pois qualquer combinação linear de polinômios cuja derivada é o negativo do próprio polinômio também satisfará essa condição. Além disso, a multiplicação por um escalar não altera a condição.

**Conclusão da Questão 3:** Todos os conjuntos (a), (b) e (c) são subespaços vetoriais de P2.

---
## Questão 4

**Quais dos conjuntos abaixo são subespaços vetoriais de R⁴? Justifique.**

**(a) W = {(x, y, z, t) em R⁴ | x + y = 0 e z - t = 0}**

**(b) W = {(x, y, z, t) em R⁴ | 2x + y - t = 0 e z = 0}**

**(c) W = {(x, y, z, t) em R⁴ | x - y - z + t = 0}**

### Resolução:

> Para um conjunto ser um subespaço vetorial, ele deve satisfazer as três condições mencionadas anteriormente: conter o vetor nulo, ser fechado sob adição e ser fechado sob multiplicação escalar.

**(a) Para W = {(x, y, z, t) em R⁴ | x + y = 0 e z - t = 0}**

- Contém o vetor nulo: Se x = y = 0 e z = t = 0, então o vetor nulo (0, 0, 0, 0) está em W.
- Fechamento sob adição: Se (x1, y1, z1, t1) e (x2, y2, z2, t2) estão em W, então (x1 + y1 = 0) e (x2 + y2 = 0), bem como (z1 - t1 = 0) e (z2 - t2 = 0). Portanto, (x1 + x2) + (y1 + y2) = 0 e (z1 + z2) - (t1 + t2) = 0, o que implica que (x1 + x2, y1 + y2, z1 + z2, t1 + t2) está em W.
- Fechamento sob multiplicação escalar: Para qualquer escalar k e vetor (x, y, z, t) em W, k(x + y) = 0 e k(z - t) = 0. Portanto, k(x, y, z, t) está em W.

Logo, W é um subespaço vetorial de R⁴.

**(b) Para W = {(x, y, z, t) em R⁴ | 2x + y - t = 0 e z = 0}**

- Contém o vetor nulo: Se x = y = z = t = 0, então o vetor nulo (0, 0, 0, 0) está em W.
- Fechamento sob adição: Similar ao anterior, se (x1, y1, 0, t1) e (x2, y2, 0, t2) estão em W, então 2(x1 + x2) + (y1 + y2) - (t1 + t2) = 0 e 0 + 0 = 0, o que é satisfeito.
- Fechamento sob multiplicação escalar: Para qualquer escalar k, o fechamento escalar será garantido.

Logo, W é um subespaço vetorial de R⁴.

**(c) Para W = {(x, y, z, t) em R⁴ | x - y - z + t = 0}**

- Contém o vetor nulo: Se x = y = z = t = 0, então o vetor nulo (0, 0, 0, 0) está em W.
- Fechamento sob adição: Se (x1, y1, z1, t1) e (x2, y2, z2, t2) estão em W, então (x1 - y1 - z1 + t1) + (x2 - y2 - z2 + t2) = 0, o que é satisfeito.
- Fechamento sob multiplicação escalar: Para qualquer escalar k, o vetor resultante também satisfaz a condição de W.

Logo, W é um subespaço vetorial de R⁴.

**Conclusão da Questão 4:** Todos os conjuntos (a), (b) e (c) são subespaços vetoriais de R⁴.

---
## Questão 5

**Expresse o vetor (1, -3, 10) em R³ como combinação linear dos vetores u = (1, 0, 0), v = (1, 1, 0) e w = (2, -3, 5).**

### Resolução:

Devemos encontrar escalares **a, b, c** tais que:

**a(1, 0, 0) + b(1, 1, 0) + c(2, -3, 5) = (1, -3, 10)**

Sistema de equações:

1. a + b + 2c = 1
2. b - 3c = -3
3. 5c = 10

Resolvendo:

- c = 2
- b - 3(2) = -3 => b = 3
- a + 3 + 2(2) = 1 => a = -6

Portanto, (1, -3, 10) = -6u + 3v + 2w.

**Conclusão da Questão 5:** (1, -3, 10) = -6u + 3v + 2w.

---
## Questão 6

**Considere os vetores v1 = (1, -3, 2) e v2 = (2, 4, -1) de R³.**

**(a) Escreva u = (-4, -18, 7) como combinação linear dos vetores v1 e v2.**

**(b) Mostre que v = (4, 3, -6) não é combinação linear dos vetores v1 e v2.**

**(c) Determine uma condição para x, y e z de modo que (x, y, z) seja combinação linear dos vetores v1 e v2.**

### Resolução:

**(a) Para u = a(1, -3, 2) + b(2, 4, -1):**

a(1, -3, 2) + b(2, 4, -1) = (-4, -18, 7)

Sistema:

1. a + 2b = -4
2. -3a + 4b = -18
3. 2a - b = 7

Resolvendo:

- Da (3), b = 2a - 7
- Substituindo na (1): a + 2(2a - 7) = -4 => 5a = 10 => a = 2
- b = 2(2) - 7 = -3

Portanto, u = 2v1 - 3v2.

**(b) Para v ser combinação linear de v1 e v2, o sistema é:**

1. a + 2b = 4
2. -3a + 4b = 3
3. 2a - b = -6

Sistema inconsistente (contradição). Logo, v não é combinação linear de v1 e v2.

**(c)** O sistema linear deve ser resolvido em termos de a e b para encontrar uma relação entre x, y, z que satisfaça as combinações lineares.

Uma solução seria: x − y − 2z = 0

---
## Questão 7

**Quais dos seguintes vetores são combinações lineares de u = (0, -2, 2) e v = (1, 3, -1)?**

**(a) (2, 2, 2)  
(b) (3, 1, 5)  
(c) (0, 4, 5)  
(d) (0, 0, 0)**

### Resolução:

Para verificar se um vetor é combinação linear de u e v, devemos resolver o sistema linear:

a(0, -2, 2) + b(1, 3, -1) = (x, y, z)

Para cada vetor:

**(a)** Resolver para (2, 2, 2):
a(0, -2, 2) + b(1, 3, -1) = (2, 2, 2)

**(b)** Resolver para (3, 1, 5):
a(0, -2, 2) + b(1, 3, -1) = (3, 1, 5)

**(c)** Resolver para (0, 4, 5):
a(0, -2, 2) + b(1, 3, -1) = (0, 4, 5)

**(d)** Resolver para (0, 0, 0):
a(0, -2, 2) + b(1, 3, -1) = (0, 0, 0)

**Conclusão da Questão 7:** Apenas os vetores (a), (b) e (d) são combinações lineares de u e v.

> O sistema da letra c) será impossível. Lembre que um sistema impossível, o posto da matriz dos coeficientes é diferente do posto da ampliada.

---
## Questão 8

**Seja S o subespaço vetorial de P2 gerado pelos vetores t, 1 - t, e 4 + t². O vetor p(t) = 3 + 4t + 10t² pertence a S? Justifique.**

### Resolução:

Para que p(t) pertença a S, devemos ter:

p(t) = a(t) + b(1 - t) + c(4 + t²)<br>
(3 + 4t + 10t²) = a(t) + b(1 - t) + c(4 + t²)

Sistema de equações:

1. -b + 4c = 3
2. a - b = 4
3. c = 10

Encontrando a, b, e c, podemos verificar que p(t) pode ser escrito como combinação linear dos vetores em S.

> Basta ver que o sistema de equações é possível.

**Conclusão da Questão 8:** Sim, p(t) pertence a S.

---
## Questão 9

**Seja P2 o espaço vetorial de todos os polinômios de grau menor ou igual a 2 com coeficientes reais.**

**(a) Mostre que {1 + t, 1 - t, t²} é base de P2.**

**(b) Escreva p(t) = 2 - t + 3t² como combinação linear dos vetores 1 + t, 1 - t, e t².**

### Resolução:

**(a)** Para mostrar que o conjunto é uma base, precisamos verificar que é linearmente independente e que gera P2.

> Existe um teorema na Álgebra Linear que diz que:<br>
> Se um conjunto tem a mesma quantidade de elementos que a dimensão do espaço e este conjunto é Li, então o conjunto é base do espaço.<br>
> Todo espaço Pn tem dimensão (n+1), logo P2 tem dimensão 3. Assim, o conjunto {1+t, 1-t, t²}, por ter 3 elementos, basta ser Li para ser base de P2.<br>
> Comprove que o conjunto dado é Li e saberemos que ele é uma base de P2.

**(b)** Precisamos resolver o sistema:

a(1 + t) + b(1 - t) + c(t²) = 2 - t + 3t²

Sistema:

1. a + b = 2
2. a - b = -1
3. c = 3

Resolva para encontrar a, b e c.

**Conclusão da Questão 9:** (a) O conjunto é uma base de P2; (b) p(t) pode ser escrito como combinação linear.

---
## Questão 10

**Quais dos conjuntos abaixo são linearmente independentes (LI)? Justifique.**

**(a) {(1, 2), (2, -1)} em R².  
(b) {(1, 1, 0), (1, -1, 1)} em R³.  
(c) {[1 1; 0 -1], [1 -1; 1 0], [1 0; 3 2]} em M(2, 2).  
(d) {[1 -1; 3 3], [-1 3; 1 5], [2 -3; 4 2]} em M(2, 2).  
(e) {t + 1, t - 1} em P1.  
(f) {t + 1, 1 + t², 1 - t + t²} em P2.**

### Resolução:

Para verificar a independência linear, montamos a matriz associada e verificamos se a única solução é a trivial (coeficientes nulos).

> Se o conjunto tiver só 2 elementos, basta provar que eles não são múltiplos um do outro.<br>
> Se o número de elementos do conjunto for maior que a dimensão do espaço, então o conjunto será LD.<br>
> Se o conjunto incluir o vetor nulo, então o conjunto será LD.<br>
> Se dois vetores do conjunto forem múltiplos um do outro, então o conjunto será LD.<br>

**Conclusão da Questão 10:** (a), (b), (c), (e), (f) são linearmente independentes, (d) é linearmente dependente.

---
## Questão 11

**Quais dos conjuntos abaixo são uma base? Justifique.**

**(a) {(1, 0, 2), (1, 1, 2), (1, 1, 4)} em R³.  
(b) {(2, 1, -1), (1, 0, -1), (1, 1, 0)} em R³.  
(c) {[1 0; 0 1], [0 1; 1 0], [1 1; 0 1], [1 0; 1 1]} em M(2, 2).  
(d) {[1 0; 0 1], [0 -1; 1 0], [1 1; 1 -1], [2 1; 1 0]} em M(2, 2).  
(e) {t, 1 + t, t - t²} em P2.  
(f) {1, 2 - t, 3 - t², t + 2t²} em P2.**

### Resolução:

> Para ser uma base de um espaço vetorial, um conjunto deve ser linearmente independente (LI) e deve gerar o espaço vetorial.

> Existe um teorema na Álgebra Linear que diz que:<br>
> Se um conjunto tem a mesma quantidade de elementos que a dimensão do espaço e este conjunto é Li, então o conjunto é base do espaço.

**Resposta da Questão 11:** Os conjuntos que são bases são (a) e (e).

---
## Questão 12

**Classifique em verdadeiro (V) ou falso (F), e justifique sua resposta.**

**(a) W = {[a b; c d] em M(2, 2) | a, b, c e d em R com b = c + 1} é um subespaço vetorial do espaço M(2, 2) das matrizes reais dois por dois.**

**(b) R² = [(1, 1), (1, -1), (0, 1)].**

**(c) (1, 0, 0) em [(1, 1, 1), (-1, 1, 0), (1, 0, -1)].**

**(d) O conjunto {(1, -1, 2), (-1, 1, 1), (0, 0, 1)} forma uma base para R³.**

### Resolução:

**Conclusão da Questão 12:** (a) F, (b) V, (c) V, (d) F.

---
## Questão 13

**Determine o(s) valor(es) de k em R de modo que:**

**(a) O vetor u = (-1, k, -7) seja combinação linear dos vetores v1 = (1, -3, 2) e v2 = (2, 4, -1).**

**(b) O conjunto {(1, 0, k), (1, 1, k), (1, 1, k²)} seja uma base de R³.**

**(c) O conjunto {(1, 0, -1), (1, 1, 0), (k, 1, -1)} seja LI em R³.**

### Resolução:

**(a)** Resolver o sistema para encontrar o valor de k que permite que u seja uma combinação linear de v1 e v2. O sistema é consistente para k = 13.

**(b)** O conjunto é uma base se e somente se for linearmente independente. Para ser linearmente independente, k não pode ser 0 ou 1.

**(c)** O conjunto é linearmente independente se o determinante da matriz formada pelos vetores for diferente de zero. Isso ocorre para todos os k diferentes de 2.

**Conclusão da Questão 13:** (a) k = 13, (b) k != 0, k != 1, (c) k != 2.

---
## Questão 14

**Classifique em verdadeiro (V) ou falso (F), e justifique sua resposta.**

**(a) O vetor v = (1, -1, 2) pertence ao subespaço gerado por u = (1, 2, 3) e v = (3, 2, 1).**

**(b) Qualquer vetor em R³ pode ser expresso como combinação linear dos vetores u = (-5, 3, 2) e v = (3, -1, 3).**

### Resolução:

**(a)** Falso. O vetor não pode ser expresso como combinação linear dos vetores dados.

**(b)** Falso. Dois vetores não podem gerar R³ porque R³ é um espaço de dimensão 3.

**Conclusão da Questão 14:** (a) F, (b) F.

---
## Questão 15

**Sejam W1 = [(1, 0, 0)] e W2 = [(1, 1, 0), (0, 1, 1)] subespaços de R³. Mostre que R³ = W1 ⊕ W2.**

> O símbolo de soma direta é ⊕<br>
> Dados dois subespaços W1 e W2 do espaço vetorial V, a soma direta entre W1 e W2 ocorre se:<br>
> A intersecção entre W1 e W2 é somente o vetor nulo.

### Resolução:

Para mostrar que R³ = W1 ⊕ W2, precisamos verificar que:

1. R³ = W1 + W2.
2. W1 ∩ W2 = {(0, 0, 0)}.

Verificação:

1. Qualquer vetor em R³ pode ser escrito como uma combinação linear dos vetores em W1 e W2.
2. A interseção é apenas o vetor nulo.

**Conclusão da Questão 15:** R³ é a soma direta de W1 e W2.

---
## Questão 16

**Encontre uma base e a dimensão do subespaço W de R³ nos casos seguintes:**

**(a) W = {(x, y, z) em R³ | x + y + z = 0}.**

**(b) W = {(x, y, z) em R³ | x = y = z}.**

### Resolução:

**(a)** A condição x + y + z = 0 define um plano em R³, que tem dimensão 2. Uma base é {(-1, 1, 0), (-1, 0, 1)}.

**(b)** A condição x = y = z define uma linha em R³. A base é {(1, 1, 1)}, com dimensão 1.

**Conclusão da Questão 16:** (a) Base: {(-1, 1, 0), (-1, 0, 1)}, Dimensão: 2. (b) Base: {(1, 1, 1)}, Dimensão: 1.

---
## Questão 17 - Gabarito

**(a)** W1 = [(1, 1, 0),(0, 0, 1)]<br>
**(b)** W2 = [(−1, −1/2, 1)]<br>
**(c)** W3 = [(−2, 1, 0),(3, 0, 1)]<br>
**(d)** W1 ∩ W2 = [(0, 0, 0)]<br>
**(e)** W2 + W3 = [(−1, −1/2, 1),(−2, 1, 0),(3, 0, 1)]<br>

---
## Questão 18 - Gabarito

**(a)** Uma base para W1 ∩ W2  é {(1/2, 1/2, 1)}. Logo, dim(W1 ∩ W2) = 1<br>
**(b)** Uma base para W1 + W2  é {(1, 0, 1),(0, 1, 1),(1, 1, 0)}. Logo, dim(W1 + W2) = 3<br>
**(c)** Sim. Justifique.<br>
**(d)** Não. Justifique.<br>

---
## Questão 19 - Gabarito

**(a)** Uma base para W1 ∩ W2  é {(0, 0, 1, 1)}. Logo, dim(W1 ∩ W2) = 1<br>
**(b)** Uma base para W1 + W2  é {(−1, 1, 0, 0),(0, 0, 1, 1),(1, 1, 0, 0),(1, 0, 1, 0)}. Logo,
dim(W1 + W2) = 4<br>
**(c)** Sim. Justifique.<br>
**(d)** Não. Justifique.<br>

---
## Questão 20 - Gabarito

[(4, -1)β] = [1, 2]<br>

---
## Questão 21 - Gabarito

**(a)** Como dim R³ = 3, basta mostrar que os vetores são LI<br>
**(b)** [5, -6, -1]<br>
**(c)** v = (2, 1, 4)<br>

---
## Questão 22 - Gabarito

[5, -3, 0]<br>

---
## Questão 23 - Gabarito

α = {(1, 5),(0, 6)}<br>

---
## Questão 24 - Gabarito

[4, 2] e [2, 1]<br>

---
## Questão 25 - Gabarito

19<br>

---
## Gabaritos das Questões Restantes

![img](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/2627.png)<br>
![img02](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/28ate30.png)
