# Polinômios

> Os polinômios são expressões matemáticas que representam a soma ou subtração entre dois ou mais monômios.

---
### Exemplos:

- **p(x) = x³ - 5x² + x - 14**
  - A variável é x
  - O coeficiente de x³ é 1
  - O coeficiente de x² é -5
  - O coeficiente de x¹ é 1
  - O termo independente é -14
  - O grau é 3

- **p(y) = y⁴ - y + 1**
  - A variável é y
  - O coeficiente de y⁴ é 1
  - O coeficiente de y³ é 0
  - O coeficiente de y² é 0
  - O coeficiente de y¹ é -1
  - O termo independente é 1
  - O grau é 4

---
### Valor numérico de um polinômio:

É o valor encontrado após substituir a variável por um número.

O valor de **p(x)** quando **x = 2** é **p(2)**, substitui a variável por 2 e calcula.

---
### Raízes:

Uma raiz de um polinômio é o valor da variável que zera o polinômio. Um polinômio pode ter uma ou mais raízes. Quando o grau é 1, tem 1 raíz. Quando o grau é 2, pode ter 2 raízes. Quando o grau é 3, pode ter 3 raízes...

---
### Polinômios idênticos:

Os coeficientes correspondentes (que acompanham a variável de mesmo grau) possuem o mesmo valor.

---
### Adição e subtração de polinômios:

Basta somar ou subtrair os termos de mesmo grau.

---
### Multiplicação:

**3 * p(x)** --> Multiplica todos os coeficientes de p(x) por 3.

---
### Divisão:

[Vídeo explicativo](https://youtu.be/WjmENMLiKbc)

---
### Fatorar com raízes:

Sendo x1 e x2 as raízes de um polinômio, podemos fatorá-lo da seguinte forma:<br>
(x - x1) * (x - x2)<br>
Se alguma das raízes tiver multiplicidade maior que 1, basta usar como expoente. Veja um exemplo em que x1, x1 e x2 são as raízes de um polinômio de grau 3:<br>

p(x) = (x - x1)² * (x - x2)

---
### Relações de Girard - 2º Grau:

x1 + x2 = -b/a<br>
x1 * x2 = c/a

### Relações de Girard - 3º Grau:

x1 + x2 + x3 = -b/a<br>
x1 * x2 * x3 = -d/a <br>
(é sempre o termo independente sobre o 'a', o sinal depende se o grau é par ou ímpar)

---
### Macete:

Quando a soma dos coeficientes for nula, então o número 1 é uma das raízes.

---
### Briot-Ruffini:

Método usado para dividir um polinômio qualquer p(x) por um polinômio da forma (x - a) ou (x + a)<br>
![briotRuffini](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/briotRuffini.png)

---
### Encontrar raízes polinômio grau 3:

Um dos divisores do termo independente será raíz do polinômio.<br>
Faça testes e descubra qual dos divisores é uma das raízes.<br>
Então, podemos dividir o polinômio por (x - raíz).<br>
O polinômio encontrado será de grau 2. Basta usar Bhaskara e encontrar as outras duas raízes.
