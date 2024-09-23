# Séries Alternadas

---
## Definição

Séries Alternadas são aquelas em que os termos alternam entre positivo e negativo. 
A forma geral de uma série alternada pode ser representada da seguinte maneira:

`∑ (-1)^n * an)`


onde a_n é uma sequência de termos positivos e (-1)^n é o fator que alterna o sinal de cada termo da série.

---
## Critérios para Convergência de Séries Alternadas

Para verificar se uma série alternada converge, podemos utilizar o **Teste das Séries Alternadas** (também chamado de **Critério de Leibniz**). Esse teste estabelece três condições que devem ser verificadas:

1. **a_n deve ser maior que zero para todo n**: Isso significa que a sequência de termos sem considerar o sinal alternado (ou seja, apenas os valores absolutos) deve ser positiva.

2. **a_n deve ser uma sequência decrescente**: A sequência de termos deve estar diminuindo conforme n aumenta. Ou seja, a_n+1 < a_n para todo n suficientemente grande.

3. **Limite de a_n deve tender a zero quando n tende ao infinito**: A sequência de termos a_n deve ter como limite o valor zero. Formalmente, isso é expresso como: lim (n -> infinito) a_n = 0.

Se as três condições acima forem satisfeitas, a série alternada converge.

---
### Exemplo de Aplicação

Vamos aplicar o **Critério de Leibniz** em uma série alternada para determinar sua convergência.

Exemplo: `∑ (-1)^n * 1/n)`


1. **a_n maior que zero**:
   - Aqui, a_n = 1/n. Como 1/n é positivo para todo n, a primeira condição é satisfeita.

2. **a_n decrescente**:
   - A sequência 1/n é decrescente conforme n aumenta, pois o denominador n está aumentando e, consequentemente, o valor de 1/n está diminuindo. Logo, a segunda condição também é satisfeita.

3. **Limite de a_n tendendo a zero**:
   - lim (n -> infinito) 1/n = 0. Isso significa que a terceira condição também é satisfeita.

Portanto, a série alternada converge.

---
## Convergência Condicional e Convergência Absoluta

Uma série alternada pode **convergir condicionalmente** ou **convergir absolutamente**.

- **Convergência Condicional**: Ocorre quando a série alternada converge, mas a série formada pelos valores absolutos dos termos não converge. Ou seja, a série converge por alternar sinais, mas se os termos fossem todos positivos, a série seria divergente.

- **Convergência Absoluta**: Se a série formada pelos valores absolutos dos termos também convergir, então a série alternada converge absolutamente. Para verificar isso, analisamos a série formada pelos módulos dos termos da série original.

---
## Teste para Convergência Absoluta

Para verificar a convergência absoluta, aplicamos os testes tradicionais de convergência, como o **Teste da Comparação**, o **Teste da Comparação Limite**, ou o **Teste da Razão**.
