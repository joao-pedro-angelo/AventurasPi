# Dicas para verificar se um conjunto é uma Base de um Espaço V.

> Uma base é um conjunto LI que gera um espaço vetorial.<br>

---
## 1. Verifique a Quantidade de Vetores

- **Criterio Inicial**: O numero de vetores no conjunto deve ser igual a **dimensao** do espaco vetorial.
  - Por exemplo, para o espaco vetorial R^3, qualquer base deve ter exatamente **3 vetores**.
  - Se o conjunto tem mais vetores do que a dimensao do espaco, ele **nao pode** ser uma base (pois os vetores seriam linearmente dependentes).

---
## 2. Verifique a Linearidade dos Vetores: Visual ou Intuitivamente

- **Linearmente Independentes**:
  - Tente observar se ha algum vetor que parece ser uma **combinacao linear** dos outros vetores.
  - Por exemplo, em R^2, os vetores (1, 0) e (0, 1) sao claramente independentes, enquanto os vetores (1, 0) e (2, 0) sao **linearmente dependentes** (pois (2, 0) = 2 * (1, 0)).

---
## 3. Caso Especial: Matrizes de Identidade

- Se voce tem um conjunto de vetores que formam a matriz identidade de ordem n (em que n e a dimensao do espaco), entao este conjunto e uma base. Por exemplo:
  - Para R^3, a matriz identidade e formada pelos vetores (1, 0, 0), (0, 1, 0), e (0, 0, 1). Esses vetores formam uma base para R^3.

---
## 4. Conheça as Bases Canônicas dos Espaços

- Base Canônica de R^n:
  - {(1, 0, 0, ... ,0); (0, 1, 0, ..., 0) ...}
  - Exemplo - R²: {(1, 0); (0, 1)}
  - Exemplo - R³: {(1, 0, 0); (0, 1, 0); (0, 0, 1)}

- Base Canônica de P^n:
  - {1, x, x², ... ,x^n}
  - Aqui, cada elemento da base é um polinômio de grau crescente, começando com o polinômio constante 1 e terminando com x^n

- Base Canônica de Matrizes:
  - Exemplo - M2x2: {(1, 0, 0, 0); (0, 1, 0, 0); (0, 0, 1, 0); (0, 0, 0, 1)}
  - Basta ir intercalando o número 1
