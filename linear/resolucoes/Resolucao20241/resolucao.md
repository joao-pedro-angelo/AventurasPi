# Resolucao da Prova 2024.1

---
## Questao 1 - a):

**a) W = {(x, y, z) em R^3 | z = xy} é um subespaco do espaco vetorial R^3.**

Para verificar se W e um subespaco vetorial, ele deve satisfazer as seguintes propriedades:

1. Conter o vetor nulo:
   - O vetor nulo em R^3 e (0, 0, 0). Para pertencer a W, z deve ser igual a xy. Neste caso, 0 = 0*0 = 0, o que significa que o vetor nulo pertence a W.

2. Fechado sob adicao:
   - Se (x1, y1, z1) e (x2, y2, z2) pertencem a W, entao z1 = x1*y1 e z2 = x2*y2.
   - Considerando a soma dos vetores, (x1 + x2, y1 + y2, z1 + z2), temos z1 + z2 = x1*y1 + x2*y2.
   - No entanto, z nao e igual a (x1 + x2)*(y1 + y2) em geral, o que mostra que W nao e fechado sob adicao.

Portanto, W nao e um subespaco de R^3.

Resposta: **Falso**

---
## Questão 1 - b):

**b) Beta = {1 + t, 2t, 3t^2} e uma base do espaco vetorial P2(R).**

Para verificar se Beta e uma base de P2(R), precisamos verificar dois criterios:
1. Linearmente independente.
2. Gera o espaco.

- Como Beta contem 3 polinomios, e P2(R) tem dimensao 3, se os polinomios forem linearmente independentes, Beta sera uma base.
- Para verificar a independencia linear, considere uma combinacao linear c1*(1 + t) + c2*(2t) + c3*(3t^2) = 0.
- Isso resulta no sistema:
  - c1 = 0
  - c1 + 2c2 = 0
  - c3 = 0
- A unica solucao para o sistema e c1 = c2 = c3 = 0, o que mostra que os vetores sao linearmente independentes.

Resposta: **Verdadeiro**

---
## Questao 2 - a)

**a) Determine a dimensao do subespaco U:**

**U = {(a + b, 2c - b, a + 2c, a) | a, b, c em R}**

Podemos reescrever cada matriz como uma combinacao linear:

M = a*(1, 0, 1, 1) + b*(1, -1, 0, 0) + c*(0, 2, 2, 0)

Os tres vetores sao linearmente independentes e geram o subespaco U, entao a dimensao de U é 3.

---
## Questão 2 - b)
**b) Encontre o valor de k tal que o vetor u = (-1, k, -7) seja uma combinacao linear dos vetores v1 e v2:**

**v1 = (1, -3, 2), v2 = (2, 4, -1)**

Precisamos resolver o sistema de equacoes:

alpha*1 + beta*2 = -1
alpha*(-3) + beta*4 = k
alpha*2 + beta*(-1) = -7

Resolvendo o sistema, obtemos k = -1.

---
## Questão 2 - c)
**c) Determine uma base para R^3 que contenha os vetores w1 e w2:**

**w1 = (1, -1, 0), w2 = (2, -1, 0)**

Os vetores w1 e w2 nao sao colineares, e podemos adicionar o vetor w3 = (0, 0, 1) para completar a base. Portanto, uma base e {(1, -1, 0), (2, -1, 0), (0, 0, 1)}.

---
## Questão 2 - d)
**d) Encontre uma base para o subespaco W1:**

**W1 = {(x, y, z) em R^3 | z = 2x + y}**

Podemos representar W1 como o conjunto de vetores {(x, y, 2x + y)}. Para formar uma base, podemos escolher dois vetores linearmente independentes, como (1, 0, 2) e (0, 1, 1).

---
## Questao 3 - a)

Considere os subespacos do R^3:

W1 = {(x, y, z) em R^3 | z = 2x + y}
W2 = {(a, a, 4a) | a em R}

**a) Determine W1 interseccao W2:**

Para encontrar a interseccao, igualamos as condicoes de W1 e W2:

z = 2x + y
z = 4a, x = a, y = a

Substituindo, temos:

4a = 2a + a
a = 0

Assim, a interseccao consiste apenas do vetor nulo (0, 0, 0).

---
## Questão 3 - b)

**b) Determine a dimensao de W1 + W2:**

Como W1 e W2 sao subespacos de R^3 e sao descritos por duas condicoes diferentes, o espaco gerado por W1 + W2 deve cobrir o R^3 inteiro. Portanto, a dimensao de W1 + W2 e 3.

---
## Questao 4:

Sejam V um espaco vetorial de dimensao 3 e {v1, v2, v3} e {w1, w2, w3} bases de V. Sabendo que [I]beta^gamma = [[1, -1, 1], [2, 0, 3], [0, 1, 0]] e u = 3v1 + v2 - 2v3, determine [u]1 e [e]2.

Para determinar as coordenadas de u nas bases {v1, v2, v3} e {w1, w2, w3}, precisamos aplicar a matriz de mudanca de base.
