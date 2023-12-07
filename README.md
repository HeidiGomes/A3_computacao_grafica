# Processamento de Imagens no Colab/Jupyter Notebook

Este programa utiliza a linguagem de programação Python e oferece um conjunto de funcionalidades para o processamento de imagens, implementado utilizando a biblioteca OpenCV. Desenvolvido no ambiente Google Colab, o código possibilita operações como translação, rotação, escalonamento, desfoque, inversão de cores, detecção de bordas, ajuste de contraste/brilho, e conversão para escala de cinza.



## Instruções de Uso:

## Google Colab:

## 1-Carregando uma Imagem:
- Faça o upload de uma imagem para o ambiente Colab.
- Especifique o caminho da imagem na seção # Carregando a imagem, substituindo '/content/pessoa.jpg' pelo caminho da sua imagem.
  python
  
image = cv2.imread('/caminho/da/sua/imagem.jpg')

## 1-Executando o Código:

- Execute todas as células do notebook.

## 2 -Interagindo com o Menu:

 - Um menu interativo permitirá que você escolha a operação desejada para o processamento da imagem.

## 3 - Continuação ou Encerramento:

 - Ao final de cada operação, escolha se deseja continuar o processamento ou encerrar o programa.

   
# Jupyter Notebook:

Caso deseje utilizar o Jupyter Notebook, siga estas etapas adicionais:

## 1 - Instalação da Biblioteca OpenCV:
Abra um terminal e execute o seguinte comando para instalar a biblioteca OpenCV.

 - pip install opencv-python
   
## 2 - Adaptação do Código:
 - No código, altere a linha de importação para:

import cv2

import numpy as np

import matplotlib.pyplot as plt

import time

- Certifique-se de que a biblioteca OpenCV está instalada no ambiente do seu Jupyter Notebook.

## Siga as Etapas 1-4 do Google Colab.
Este programa proporciona uma experiência interativa de processamento de imagens, permitindo que você explore diversas operações de forma fácil e eficaz. Sinta-se à vontade para ajustar o código conforme necessário e aproveitar as capacidades de processamento de imagem oferecidas.






