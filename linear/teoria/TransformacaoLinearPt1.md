# Transformacoes Lineares

Este documento aborda conceitos e exemplos de transformacoes lineares, conforme as questoes resolvidas.

---
## Definicao de Transformacao Linear

Uma transformacao linear T: V -> W, onde V e W sao espacos vetoriais, deve satisfazer duas propriedades principais:

1. **Aditividade**: T(u + v) = T(u) + T(v) para todos os vetores u, v pertencentes a V.
2. **Homogeneidade**: T(c * u) = c * T(u) para todo escalar c e vetor u pertencente a V.

Essas propriedades garantem que a transformacao preserva a estrutura linear do espaco vetorial.

---
## Verificacao de Transformacoes Lineares

### Exemplo 1

Para determinar se uma transformacao e linear, devemos testar as propriedades de aditividade e homogeneidade. 

#### Funcao: T: R^2 -> R^2

Exemplo de transformacao:
T(x, y) = (x + y, x - y)

Verificamos a linearidade:

- **Aditividade**: Dado T((x1, y1) + (x2, y2)), temos que:
  T(x1 + x2, y1 + y2) = ((x1 + x2) + (y1 + y2), (x1 + x2) - (y1 + y2)) = T(x1, y1) + T(x2, y2)

- **Homogeneidade**: Para um escalar c:
  T(c(x, y)) = T(cx, cy) = (cx + cy, cx - cy) = c(x + y, x - y) = c * T(x, y)

Como ambas as propriedades sao satisfeitas, a funcao e uma transformacao linear.

---
### Exemplo 2

#### Funcao: T: R^3 -> R^2

Considere a transformacao:
T(1, 0, 0) = (2, 0), T(0, 1, 0) = (1, 1), T(0, 0, 1) = (0, -1)

Para determinar a transformacao T(v) onde v = (3, 2, 1), podemos escrever v como combinacao linear dos vetores base:

v = 3(1, 0, 0) + 2(0, 1, 0) + 1(0, 0, 1)

Pela linearidade, temos:

T(3, 2, 1) = 3 * T(1, 0, 0) + 2 * T(0, 1, 0) + 1 * T(0, 0, 1)

Substituindo os valores:

T(3, 2, 1) = 3(2, 0) + 2(1, 1) + 1(0, -1) = (6, 0) + (2, 2) + (0, -1) = (8, 1)

Portanto, T(3, 2, 1) = (8, 1).

---
## Exemplo 3: Polinomios

Para transformacoes envolvendo polinomios, as mesmas propriedades de linearidade se aplicam. 

#### Funcao: T: P2 -> P2

Seja a transformacao definida por:
T(p(t)) = p''(t) * t^2

Vamos verificar se esta transformacao e linear:

- **Aditividade**: Para p(t), q(t) pertencentes a P2, temos que:
  T(p(t) + q(t)) = (p(t) + q(t))'' * t^2 = (p''(t) + q''(t)) * t^2 = p''(t) * t^2 + q''(t) * t^2 = T(p(t)) + T(q(t))

- **Homogeneidade**: Para c pertencente a R:
  T(c * p(t)) = (c * p(t))'' * t^2 = c * p''(t) * t^2 = c * T(p(t))

Como ambas as propriedades sao satisfeitas, T e uma transformacao linear.

---
## Determinando Transformacoes

Quando temos uma transformacao T com exemplos fornecidos para vetores de base, podemos determinar o comportamento da transformacao em outros vetores expressando-os como combinacoes lineares dos vetores de base conhecidos.

Exemplo:
Se T(0, 1, 2) = 6 - t + t^2, T(1, 1, 0) = 2 - t e T(0, 0, 1) = t, entao para encontrar T(1, 2, 3), escrevemos (1, 2, 3) como uma combinacao linear dos vetores dados:

(1, 2, 3) = a(0, 1, 2) + b(1, 1, 0) + c(0, 0, 1)

Resolvendo o sistema linear, determinamos os coeficientes e aplicamos a linearidade da transformacao para calcular T(1, 2, 3).

---
## Conclusao

As transformacoes lineares preservam a aditividade e a homogeneidade, caracteristicas fundamentais para garantir que operacoes em espacos vetoriais sejam mantidas de maneira consistente. Atravess dos exemplos abordados, fica claro como essas propriedades podem ser usadas para verificar a linearidade e calcular a imagem de vetores sob uma transformacao linear.
