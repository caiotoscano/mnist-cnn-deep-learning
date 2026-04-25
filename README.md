# MNIST CNN - Classificação de Dígitos Manuscritos

## Visão Geral

Este projeto tem como objetivo desenvolver e avaliar modelos de Deep Learning para classificação de dígitos manuscritos utilizando o dataset MNIST. Ao longo dos notebooks, foi construída uma evolução progressiva de modelos, desde a compreensão inicial dos dados até a aplicação de técnicas avançadas como Data Augmentation e otimização de hiperparâmetros.

O foco do projeto está não apenas na performance final, mas também na construção de uma base sólida em Redes Neurais Convolucionais (CNN) e boas práticas de organização e experimentação.

---

## Objetivos

- Compreender a estrutura e características do dataset MNIST
- Implementar modelos baseados em Redes Neurais Convolucionais
- Explorar técnicas de melhoria de generalização
- Aplicar estratégias de otimização de hiperparâmetros
- Estruturar um fluxo de experimentação progressivo e organizado

---

## Tecnologias Utilizadas

- Python
- Jupyter Notebook
- TensorFlow / Keras
- NumPy
- Matplotlib
- Keras Tuner

---

## Dataset

O dataset MNIST é composto por 70.000 imagens em escala de cinza de dígitos manuscritos (0 a 9), com dimensão de 28x28 pixels. Trata-se de um dos conjuntos de dados mais utilizados para benchmarking em tarefas de classificação de imagens.

---

## Redes Neurais Convolucionais

As Redes Neurais Convolucionais (CNNs) são amplamente utilizadas em tarefas de visão computacional por sua capacidade de capturar padrões espaciais em imagens. Elas utilizam camadas convolucionais para extração de características, seguidas por camadas de pooling para redução dimensional e camadas densas para classificação.

Neste projeto, diferentes arquiteturas de CNN foram exploradas para avaliar impacto em desempenho e generalização.

---

## Estrutura do Projeto

O projeto foi organizado em notebooks sequenciais, refletindo a evolução do aprendizado e das abordagens utilizadas:

### 00_sobre_a_base.ipynb
- Exploração inicial do dataset MNIST
- Visualização de imagens
- Análise da distribuição dos dados
- Preparação e pré-processamento

### 16_cnn_average_pooling.ipynb
- Implementação de uma CNN básica
- Introdução ao conceito de pooling
- Avaliação do impacto do Average Pooling
- Treinamento e análise de métricas

### 20_mnist_cnn_terceiro_modelo_data_augmentation.ipynb
- Construção de um modelo mais robusto
- Aplicação de Data Augmentation
- Melhoria da capacidade de generalização
- Comparação com modelos anteriores

### 21_mnist_keras_tunner.ipynb
- Utilização do Keras Tuner para otimização de hiperparâmetros
- Exploração automática de combinações de parâmetros
- Identificação da melhor configuração de modelo
- Avaliação final de performance

---

## Resultados

Ao longo do projeto, foi possível observar uma evolução consistente na performance dos modelos. A aplicação de técnicas como Data Augmentation e Hyperparameter Tuning contribuiu significativamente para a melhoria da generalização e estabilidade dos resultados.

---

## Principais Aprendizados

- Importância da exploração inicial dos dados
- Impacto da arquitetura da rede na performance
- Benefícios do uso de Data Augmentation
- Relevância da otimização de hiperparâmetros
- Organização de experimentos em etapas progressivas

---

## Possíveis Melhorias

- Testar arquiteturas mais complexas (ResNet, EfficientNet)
- Implementar validação cruzada
- Realizar deploy do modelo em uma API
- Criar interface para inferência em tempo real
- Expandir para outros datasets de visão computacional

---

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/mnist-cnn-deep-learning.git
