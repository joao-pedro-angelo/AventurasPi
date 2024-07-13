# Forma Escada

Toda matriz possue uma única forma escada. Para que uma matriz esteja na sua forma escada, é preciso
que os 4 pontos abaixos sejam satisfeitos.

1. O *primeiro elemento não nulo* de cada *linha não nula* deve ser 1;
2. Cada coluna que contém o elemento não nulo deve ter todos os outros elementos iguais a 0;
3. Toda linha nula, se houver, deve vir abaixo das não-nulas;
4. O elemento não nulo da linha 1 deve estar em uma coluna menor que o da linha 2 e assim por diante.

É o ponto 4 que dá a aparência de escada à matriz.

Veja abaixo exemplos de matrizes escadas:<br>
![img01](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/MatrizEscada01.png)<br>
![img02](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/MatrizEscada02.png)<br>
![img03](https://github.com/joao-pedro-angelo/AventurasPi/blob/main/imgs/MatrizEscada03.png)<br>

---
# Posto

O posto de uma Matriz A (p), é o *número de linhas não nulas* da *forma escada* da Matriz A.

---
# Nulidade

A nulidade de uma Matriz A, é o número de colunas da matriz subtraído do posto (n - p). 
