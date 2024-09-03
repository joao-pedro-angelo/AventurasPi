# Como verificar se um conjunto é gerador de um espaço v.

Para verificar se um conjunto de vetores é um gerador de um espaço vetorial de forma mais intuitiva, considere as seguintes dicas e propriedades:

---
## 1. Entenda a Dimensão do Espaço

Conheça a dimensão do espaço vetorial `V`. Por exemplo:
- `R^2` tem dimensão 2.
- `R^3` tem dimensão 3.
- O espaço de polinômios de grau até `n` tem dimensão `n+1`.

---
## 2. Verifique a Linearidade

Verifique se o número de vetores no conjunto é pelo menos igual à dimensão do espaço vetorial. Se você tem um conjunto de vetores que tem menos vetores do que a dimensão do espaço, eles não podem ser um gerador completo do espaço.

### Exemplo:
- No espaço `R^2`, um conjunto de dois vetores pode gerar `R^2`.
- No espaço `R^3`, você precisa de três vetores para gerar o espaço.

---
## 3. Cheque a Linearidade Independente

Se possível, verifique se os vetores são linearmente independentes:
- Se os vetores são linearmente independentes e o número de vetores é igual à dimensão do espaço, eles são um gerador.

### Dica:
- Dois vetores em `R^2` são linearmente independentes se não forem múltiplos um do outro.
- Três vetores em `R^3` são linearmente independentes se nenhum vetor puder ser escrito como combinação linear dos outros dois.

---
## 4. Propriedade de Geração

Se você conhece que um conjunto de vetores é um conjunto base (ou seja, é linearmente independente e tem a mesma dimensão que o espaço), então ele é um gerador do espaço.

### Dica:
- Um conjunto de vetores que forma uma base é sempre um gerador. Você pode confirmar isso verificando a base em vez de calcular combinações lineares diretamente.

---
## 5. Conjunto com mais elementos que a dimensão do espaço

Se o conjunto de vetores tem mais elementos do que a dimensão do espaço vetorial, ele ainda pode ser um gerador,
mas ele não é linearmente independente.
Neste caso, o conjunto de vetores é chamado de superconjunto ou conjunto redundante.

---
## 6. Exemplos Simples

Aqui estão alguns exemplos simples para verificar sem muitos cálculos:
- **Em `R^2`**: { (1,0), (0,1) } é um gerador de `R^2`.
- **Em `R^3`**: { (1,0,0), (0,1,0), (0,0,1) } é um gerador de `R^3`.

