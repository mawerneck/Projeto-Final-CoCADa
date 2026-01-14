# 🔍 Emotion Recognition from Facial Images 
Este projeto implementa um **algoritmo de reconhecimento automático de emoções faciais** a partir de imagens de rostos em escala de cinza e previamente padronizadas.

## 🖊️ Como funciona 
O algoritmo recebe uma **imagem-alvo de um rosto** e retorna qual emoção ela expressa entre um conjunto pré-definido de classes emocionais (como *Happy, Sadness, Anger, Surprise, Neutral*, entre outras). A decisão é tomada com base em padrões aprendidos a partir de um conjunto de imagens rotuladas.

De forma geral, o sistema:
- Reduz dimensionalidade das imagens do dataset usando **EigenFaces**
- Aprende representações características de rostos humanos a partir de um dataset de treinamento via **Logistic Regression**
- Compara uma nova imagem com essas representações aprendidas  
- Estima a emoção mais provável associada ao rosto apresentado  

## 📌 Objetivo
O foco do projeto é demonstrar como técnicas de **redução de dimensionalidade** e **classificação supervisionada** podem ser combinadas para resolver um problema real de visão computacional e análise de dados.

## 📁 Materiais 

Este repositório contém o código-fonte, experimentos e visualizações utilizados no desenvolvimento do Trabalho Final da disciplina **Computação Científica e Análise de Dados (CoCADA)**.
