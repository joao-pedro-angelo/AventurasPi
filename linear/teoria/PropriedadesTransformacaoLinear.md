# Propriedades de uma Transformacao Linear

---
Uma **transformacao linear** é uma funcao que mapeia vetores de um espaco vetorial V para outro espaco vetorial W,
preservando duas propriedades essenciais: a **aditividade** e a **homogeneidade**. 

Essas propriedades sao fundamentais para que a estrutura de espaco vetorial seja mantida.

---
## Definicao

Uma funcao T: V -> W é dita uma **transformacao linear** se, para todos os vetores u e v pertencentes a V e para todo escalar c pertencente a R, as seguintes propriedades forem satisfeitas:

1. **Aditividade**: T(u + v) = T(u) + T(v)
2. **Homogeneidade**: T(c * u) = c * T(u)

---
## Outras Propriedades Derivadas

A partir das duas propriedades fundamentais, podemos derivar algumas outras propriedades importantes de uma transformacao linear:

### 1. Transformacao do Vetor Nulo

Para qualquer transformacao linear T: V -> W, o vetor nulo de V sempre sera mapeado para o vetor nulo de W. Isto e, T(0_V) = 0_W. Isso pode ser demonstrado usando a propriedade da homogeneidade:

- T(0_V) = T(0 * u) = 0 * T(u) = 0_W
