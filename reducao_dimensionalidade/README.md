# Desafio de Projeto: Redução de Dimensionalidade em imagem

## Conversão de Imagem: Colorida → Cinza → Preto e Banco (Binarizada)



Desafio do bootcamp de Machine Learning que consiste em:



- Ler uma imagem colorida;

- Converter para escala de cinza (tons de 0 a 255);

- Binarizar a imagem (preto e branco: 0 ou 255), sem uso de bibliotecas externas.





## Lógica aplicada



- Para tons de cinza, usamos a fórmula:

```

gray = 0.299 \* R + 0.587 \* G + 0.114 \* B

```



- Para imagem em preto e banco, aplicamos um threshold:

```

if gray >= 127 → 255 (branco)

else → 0 (preto)

```





Desafio realizado com foco em aprendizado da lógica de processamento de imagem sem uso de bibliotecas prontas.







