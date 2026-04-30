# 👁️ PBL Fase 6 - Visão Computacional | FIAP

Este repositório contém a solução prática desenvolvida para o PBL (Project-Based Learning) da Fase 6 do curso de Inteligência Artificial da FIAP. 

O projeto foi construído para atender à demanda da empresa fictícia **FarmTech Solutions**, demonstrando a aplicabilidade de sistemas de Visão Computacional para detecção e classificação de objetos no mundo real.

## 🎯 Objetivo do Projeto
O desafio consistiu em capturar um dataset próprio contendo dois objetos distintos (uma **caneca** e um **relógio**) e avaliar o desempenho de diferentes arquiteturas de Inteligência Artificial na tarefa de reconhecê-los e classificá-los. 

## 🛠️ Tecnologias e Abordagens Utilizadas
Durante o projeto, foram exploradas e comparadas três abordagens principais:
1. **YOLOv5 (Customizado):** Treinamento de uma rede neural de detecção de objetos (bounding boxes) utilizando um dataset próprio rotulado no Make Sense AI, testado com 30 e 60 épocas.
2. **YOLOv5 (Padrão/Pré-treinado):** Teste de inferência utilizando os pesos originais do dataset COCO (`yolov5s.pt`) para fins de comparação de *Transfer Learning*.
3. **CNN do Zero (Keras/TensorFlow):** Construção e treinamento de uma Rede Neural Convolucional clássica para a tarefa de classificação binária das imagens (sem detecção de coordenadas).

## 📂 Estrutura do Repositório
Para melhor organização e execução dos códigos, o projeto foi dividido em dois diretórios e notebooks independentes:

* **📁 Projeto YOLO (Detecção de Objetos):**
  * `JoaoAlves_rm562376_pbl_fase6.ipynb`: Notebook focado na preparação do ambiente, treinamento e testes práticos comparando o YOLOv5 Customizado e o YOLOv5 Padrão.

* **📁 Projeto CNN (Classificação de Imagens):**
  * `JoaoAlves_rm562376_pbl_fase6cnn.ipynb`: Notebook dedicado à construção arquitetural, compilação e inferência da Rede Neural Convolucional criada do zero utilizando TensorFlow/Keras.

## 🎥 Demonstração em Vídeo
No vídeo abaixo, demonstro o funcionamento do código, a estrutura dos datasets e os resultados finais de predição gerados pelas Inteligências Artificiais desenvolvidas.

▶️ **[Clique aqui para assistir ao vídeo de demonstração no YouTube](https://www.youtube.com/watch?v=k13tQpIoOb4)**

---
**GRUPO:** 
João Pedro Nishikawa Alves - RM: [562376]
Guilherme Filartiga Pereira da Silva — RM: [568034]
