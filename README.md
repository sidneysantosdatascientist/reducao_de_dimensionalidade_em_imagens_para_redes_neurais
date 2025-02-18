Projeto: Conversão de Imagens Coloridas para Níveis de Cinza e Binarização

Este projeto implementa um algoritmo em Python para converter imagens coloridas em tons de cinza e, em seguida, binarizá-las (preto e branco). O objetivo é realizar as transformações sem o uso de bibliotecas especializadas para processamento de imagens, como OpenCV ou PIL, implementando as funções manualmente.

Funcionalidades

Conversão de RGB para tons de cinza:

Utiliza a fórmula ponderada para calcular o valor de cinza de cada pixel:
.

Binarização da imagem:

Aplica um limiar (threshold) para transformar os tons de cinza em preto (0) ou branco (255).

Visualização das imagens:

Exibe a imagem original, a imagem em tons de cinza e a imagem binarizada lado a lado para comparação.

Requisitos

Python 3.7 ou superior

Google Colab (ou qualquer IDE que suporte execução de código Python)

Bibliotecas Necessárias

As seguintes bibliotecas serão usadas:

NumPy: Para manipulação de arrays e cálculos matemáticos.

Matplotlib: Para exibição das imagens.

Google Colab Files: Para realizar upload da imagem no ambiente Colab.
