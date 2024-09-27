# Conceitos Relacionados às Transformacoes Lineares

As transformacoes lineares sao funcoes que preservam a estrutura dos espacos vetoriais, ou seja, elas mantem a adicao de vetores e a multiplicacao por escalares. Varios conceitos estao associados a essas transformacoes, e entender cada um deles é crucial para compreender o comportamento dessas funcoes.

---
## 1. Imagem de uma Transformacao Linear

A **imagem** de uma transformacao linear T: V -> W é o conjunto de todos os vetores de W que sao alcancaveis pela aplicacao de T em vetores de V. Formalmente, a imagem e definida como:

- **Im(T) = {T(v) | v pertence a V}**

A imagem representa todos os vetores que podem ser obtidos por meio da transformacao linear. Ela forma um subespaco vetorial de W.

### Exemplo:
Se T: R^2 -> R^2 for dada por T(x, y) = (x + y, 2x), entao a imagem de T sera o conjunto de todos os vetores (x + y, 2x) para todo vetor (x, y) pertencente a R^2.

---
## 2. Nucleo de uma Transformacao Linear

O **nucleo** de uma transformacao linear T: V -> W é o conjunto de todos os vetores de V que sao mapeados para o vetor nulo de W. Formalmente, o nucleo e definido como:

- **Nucleo(T) = {v pertence a V | T(v) = 0_W}**

O nucleo indica todos os vetores que sao "anulados" pela transformacao, ou seja, que sao mapeados para o zero. Ele tambem forma um subespaco vetorial de V.

### Exemplo:
Se T: R^2 -> R^2 for dada por T(x, y) = (x + y, 0), o nucleo sera o conjunto de vetores (x, y) tal que x + y = 0, ou seja, Nucleo(T) = {(x, -x) | x pertence a R}.

---
## 3. Injetividade de uma Transformacao Linear

Uma transformacao linear T: V -> W é **injetora** se vetores distintos de V sao mapeados para vetores distintos em W. Para que T seja injetora, o nucleo de T deve conter apenas o vetor nulo, ou seja:

- **T e injetora se, e somente se, Nucleo(T) = {0_V}**

Em outras palavras, T é injetora quando nao ha dois vetores diferentes de V que sejam mapeados para o mesmo vetor em W.

### Exemplo:
Se T: R^2 -> R^2 for dada por T(x, y) = (x + y, 2x), T nao sera injetora, pois vetores diferentes podem ser mapeados para o mesmo vetor, indicando que o nucleo contem mais de um elemento.

---
## 4. Sobretividade de uma Transformacao Linear

Uma transformacao linear T: V -> W é **sobretora** se sua imagem for igual ao espaco de chegada W. Ou seja, T é capaz de atingir todos os vetores em W:

- **T e sobretora se Im(T) = W**

Para que uma transformacao seja sobretora, sua imagem deve preencher completamente o espaco de chegada.

### Exemplo:
Se T: R^2 -> R^2 for dada por T(x, y) = (x + y, 2x), T nao sera sobretora, pois nem todos os vetores de R^2 podem ser expressos como (x + y, 2x).

---
## 5. Isomorfismo

Uma transformacao linear T: V -> W é um **isomorfismo** se for simultaneamente injetora e sobretora, ou seja, se ela for bijetora. Isso significa que T estabelece uma correspondencia um-para-um entre os vetores de V e os vetores de W, preservando a estrutura vetorial.

Se T for um isomorfismo, V e W sao considerados **isomorfos**, o que significa que eles sao essencialmente o mesmo espaco vetorial, embora possam ser representados de formas diferentes.

### Exemplo:
Se T: R^2 -> R^2 for dada por T(x, y) = (x, y), T e um isomorfismo, pois mapeia cada vetor de R^2 de forma unica e completa.

---
