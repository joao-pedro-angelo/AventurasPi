# Limites de Sequências

---
## Definição

O limite de uma sequência é o valor para o qual os termos da sequência tendem à medida que `n` (a posição do termo) cresce indefinidamente.

Matematicamente, dizemos que:<br>
`lim (n -> infinito) an = L`

Se não existe tal número `L`, dizemos que a sequência **diverge**.


---
## Propriedades dos Limites

#### 1. Limite de uma Soma

Se `{an}` e `{bn}` são duas sequências que possuem limites finitos, então o limite da soma das duas sequências é igual à soma dos limites.

#### 2. Limite de um Produto

Se `{an}` e `{bn}` têm limites finitos, o limite do produto das duas sequências é o produto dos limites.

#### 3. Limite de uma Divisão

Se `{an}` e `{bn}` têm limites finitos e `lim (n -> infinito) bn ≠ 0`, o limite da divisão das sequências é a divisão dos limites.

#### 4. Limite de uma Constante

Se `c` é uma constante, o limite de uma constante é a própria constante.

#### 5. Limite de uma Sequência Multiplicada por uma Constante

Se `{an}` é uma sequência com limite finito e `c` é uma constante, então o limite da sequência multiplicada por `c` é `c` vezes o limite da sequência.

#### 6. Limite de uma Constante sobre n

Se `{an} = K/n{`, então o limite será 0.

#### 7. Limite Exponencial

Se `{an} = k^n`, então o limite será infinito.


---
## Como Calcular Limites de Sequências

#### 1. Dividir pelos Termos de Maior Grau

Para sequências polinomiais ou racionais, uma técnica comum é dividir todos os termos pelo maior grau de `n`. Isso facilita a identificação do comportamento assintótico da sequência.

Considere a sequência `an = (3n^2 + 2) / (n^2 + 1)`. Dividindo o numerador e o denominador por `n^2`, obtemos:<br>
`an = 3/1`

`lim (n -> infinito) an = 3 / 1 = 3`

#### 2. Utilizar as Propriedades dos Limites

Como discutido anteriormente, as propriedades dos limites podem ser usadas para simplificar o cálculo.

---
## Teorema do Confronto

![img01](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/TeoremaConfrontoSequencias.png)

![img02](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/MaisExemplosTeoremaConfrontoSeq.png)

---
## Teorema da Função Contínua

![img03](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/teoremaDaFuncaoContinua.png)
