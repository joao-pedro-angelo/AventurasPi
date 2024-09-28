# Dicas para a Prova 3

---
## Questões para provar que é uma transformação linear

Basta provar duas igualdade:
1. `T(a) + T(b) = T(a + b)`, sendo `a` e `b` elementos do domínio.
2. `c * T(a) = T(a * c)`, sendo `c` um número real qualquer e `a` um elemento do domínio.

> Macete: Quando a transformação envolver produtos notáveis, há grandes chances de não ser transformação.<br>
> Veja:

![image](https://github.com/user-attachments/assets/834260d2-384a-4ab5-8f20-6973ef728f1f)<br>
> Termos do tipo (a + b)², (a + b)³, são produtos notáveis. 

---
## Questões para encontrar determinado vetor que satisfaça uma transformação

Use as bases canônicas ou os vetores dados na questão. Veja:
1. Base canônica de R²: `(1, 0) e (0, 1)`
2. Base canônica de R³: `(1, 0, 0), (0, 1, 0), (0, 0, 1)`

Escreva `T(v)`, sendo `v` o vetor que se quer encontrar e `T()` a transformação, em função da base canônica.

![image](https://github.com/user-attachments/assets/206b1065-9279-4810-88ad-4470398ac031)<br>
![image](https://github.com/user-attachments/assets/e808f06e-6578-41fc-b031-f6b53ca1809a)<br>
![image](https://github.com/user-attachments/assets/0961b858-d3fb-4f86-bd9b-131a72b25651)

---
## Encontrar o Conjunto Gerador da Imagem de uma transformação

![image](https://github.com/user-attachments/assets/cffad1b4-4ced-4c16-bf82-fa4c22583f18)

O Conjunto Gerador encontrado irá gerar todo o conjunto imagem.

---
## Encontrar a Imagem de uma transformação

> A imagem são os elementos do contradomínio que são mapeados por algum elemento do domínio.

![image](https://github.com/user-attachments/assets/cb0082a2-9db8-43de-9045-cc79431b4969)

A dimensão será a quantidade de elementos da base do conjunto imagem, no caso acima, 2.

---
## Encontrar o Núcleo de uma transformação

> O núcleo de uma transformação são os elementos do domínio que levam ao vetor nulo do contradomínio.<br>
> O núcleo também pode ser chamado de Kernel.

![image](https://github.com/user-attachments/assets/65bc1c85-c1de-411c-acde-b966beed10ac)

Pega a transformação e iguala ao vetor nulo do contradomínio.<br>
A dimensão do Kernel será a quantidade de elemento diferentes do vetor nulo do núcleo.

![image](https://github.com/user-attachments/assets/6465c418-9cf0-4503-95a6-8b37e8f20de7)

---
