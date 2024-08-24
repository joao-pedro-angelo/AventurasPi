# Método do Anel - Cálculo do Volume de Sólidos de Rev.

---
## Quando usar?

### Método do Anel
Geralmente usa duas curvas: O método do anel é usado quando duas curvas definem a região a ser girada em torno de um eixo.

**Características:**
1. Há uma curva interna e uma curva externa em relação ao eixo de rotação.
2. A região entre as duas curvas cria um anel quando girada, resultando em um sólido com um "furo" ou espaço vazio no centro.
3. O volume é calculado subtraindo o volume formado pela curva interna do volume formado pela curva externa.

**Método do Disco:** Uma curva delimitando a região (volume sólido sem buraco).<br>
**Método do Anel:** Duas curvas delimitando a região (volume com um buraco no centro).

---
## Passo a Passo

1. Identificar as funções que serão rotacionadas;
2. Identificar qual o eixo de rotação;
3. Verificar qual função será o raio externo (é a que está mais distante do eixo de rotação);
4. Verificar qual função será o raio interno (é a que está mais próxima do eixo de rotação);
5. Montar a fórmula do volume (V = π(R² - r²)), sendo **R** o raio externo e **r** o raio interno; 
6. Montar a integral;

---
## Exemplo 1

> A região delimitada pela curva g(x) = X² + 1 e pela reta f(x) = -X + 3 gira em torno do eixo X, gerando um sólido.<br>
> Determine a integral que calcula o volume deste sólido.

Primeiro, vamos montar o gráfico:<br>
![img01](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/00000.png)

**Agora, identifique os limites de integração:** <br>
Basta fazer g(x) = f(x)<br>
X² + 1 = -X + 3<br>
Iremos encontrar X = -2 e X = 1

**Agora, identifique o raio externo e o raio interno:** <br>
O raio externo é a função que está mais distante do eixo de rotação, que nesta questão é o X.<br>
Como podemos ver no gráfico, o raio externo é **-X + 3**;<br>
O raio interno é **X² + 1**;<br>

Assim, a integral que calcula o volume do sólido é:<br>
![img02](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/240801.png)

---
## Exemplo 2
