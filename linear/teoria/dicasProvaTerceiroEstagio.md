# Dicas para a Terceira Prova - pt1

---
## Questões para provar que é uma transformação linear

![image](https://github.com/user-attachments/assets/06028b53-97aa-44ed-af1f-88272c6b8915)<br>
![image](https://github.com/user-attachments/assets/ad70e1ee-8132-4b99-977c-014dca369165)

Basta provar duas igualdade:
1. `T(a) + T(b) = T(a + b)`, sendo `a` e `b` elementos do domínio.
2. `c * T(a) = T(a * c)`, sendo `c` um número real qualquer e `a` um elemento do domínio.

> Macete: Quando a transformação envolver produtos notáveis, há grandes chances de não ser transformação.<br>
> Veja:

![image](https://github.com/user-attachments/assets/834260d2-384a-4ab5-8f20-6973ef728f1f)<br>
> Termos do tipo (a + b)², (a + b)³, são produtos notáveis. 

---
## Encontrar determinado elemento

![image](https://github.com/user-attachments/assets/76950455-0003-42d9-8051-d3b44f53a83b)<br>
![image](https://github.com/user-attachments/assets/ddbc8a8c-7411-4d3c-be0e-b433e5602eee)

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

A dimensão será a quantidade de elementos da base do conjunto imagem, no caso acima, 2.<br>
O posto da transformação é a dimensão do conjunto imagem.

---
## Encontrar o Núcleo de uma transformação

> O núcleo de uma transformação são os elementos do domínio que levam ao vetor nulo do contradomínio.<br>
> O núcleo também pode ser chamado de Kernel.

![image](https://github.com/user-attachments/assets/65bc1c85-c1de-411c-acde-b966beed10ac)

Pega a transformação e iguala ao vetor nulo do contradomínio.<br>
A dimensão do Kernel será a quantidade de elemento diferentes do vetor nulo do núcleo.

![image](https://github.com/user-attachments/assets/6465c418-9cf0-4503-95a6-8b37e8f20de7)<br>

Veja um exemplo com matriz:<br>
![image](https://github.com/user-attachments/assets/02a74910-a4d2-4e0c-aceb-763c71f73c02)<br>
![image](https://github.com/user-attachments/assets/494544ab-880c-494d-a237-9cef356a2e06)

---
## Injetividade

> Uma função é injetora, se não há imagens idênticas para diferentes elementos do domínio.

![image](https://github.com/user-attachments/assets/d8ddd1c9-18e2-489d-8b52-98e983fe9896)<br>
![image](https://github.com/user-attachments/assets/e680c99a-5e6f-4772-a8ee-e67997cbd05b)

> Logo, para identificar injetividade, basta descobrir se o núcleo da transformação é formado apenas pelo vetor nulo.

![image](https://github.com/user-attachments/assets/b4b67588-8ff1-44d7-9a98-6f90b043cc85)<br>

---
## Sobrejetividade

> Uma função é sobrejetora se o conjunto imagem é igual ao contradomínio.

![image](https://github.com/user-attachments/assets/dc0d5678-0130-4716-bc12-d8881a60f6f2)<br>
![image](https://github.com/user-attachments/assets/d614b87f-d312-486e-aad1-9be419876941)

![image](https://github.com/user-attachments/assets/ce135e2c-909f-46d3-b75b-84e7a1a3e28f)

> Logo, para identificar se a função é sobrejetora, basta ver se a dimensão do conjunto imagem é igual a dimensão do domínio.

---
## Conclusão desta Parte 1

1. Provar que é Transformação Linear
2. Identificar determinado elemento
3. Identificar um vetor que satisfaz uma condição
4. Conjunto Imagem e seu gerador
5. Núcleo
6. Injetividade
7. Sobrejetividade
