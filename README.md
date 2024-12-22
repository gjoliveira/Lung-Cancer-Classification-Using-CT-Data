# Lung-Cancer-Classification-Using-CT-Data


## Sobre o Projeto

Este projeto foi focou-se na classificação da malignidade de cancro do pulmão utilizando imagens de tomografia computorizadas (CT). A solução emprega metodologias avançadas de ciência de dados e técnicas de machine learning para apoiar o diagnóstico precoce, aumentando as taxas de sobrevivência através de uma avaliação automática da malignidade de nódulos pulmonares.

## Contexto e Motivação

O cancro do pulmão é uma das principais causas de mortalidade relacionada com cancro a nível global. O diagnóstico precoce melhora significativamente as taxas de sobrevivência, mas a maioria dos casos é detectada em estádios avançados. Este projeto aborda estes desafios ao utilizar imagens de CT para desenvolver um sistema de diagnóstico assistido por computador (CAD) capaz de prever a malignidade de nódulos pulmonares com alta precisão, reduzindo a dependência de avaliações visuais subjetivas por parte dos radiologistas.

## Funcionalidades

Preprocessamento de Dados: Conversão e limpeza do conjunto de dados LIDC-IDRI para extrair características relevantes e preparar os dados para análise.

Engenharia de Características: Extração de características baseadas em radiómica combinadas com características derivadas de deep learning.

Modelos de Classificação: Implementação de modelos de machine learning, incluindo Random Forest, Support Vector Machines (SVM) e Redes Neuronais Convolucionais (CNN).

Otimização de Modelos: Ajuste de hiperparâmetros e seleção de modelos para desempenho ótimo.

Visualização: Visualização abrangente de scans de CT, máscaras de segmentação e resultados de modelos.

Interpretação de Modelos: Ênfase na interpretabilidade e equidade para garantir confiabilidade em aplicações clínicas.

## Tecnologias Utilizadas

Linguagem de Programação: Python (utilizando bibliotecas como NumPy, Pandas, Scikit-learn, TensorFlow/Keras, Matplotlib e Pyradiomics).

Conjunto de Dados: LIDC-IDRI, um conjunto de dados de CT torácico com nódulos anotados.

Frameworks e Ferramentas: Pylidc, Pyradiomics, bibliotecas DICOM para manipulação e processamento de dados.

## Considerações Éticas e Legais

Cumprimento das leis de privacidade de dados (ex.: GDPR, HIPAA) na manipulação de dados médicos.

Relatório transparente dos resultados para evitar interpretações clínicas enganosas.

Conformidade com futuros quadros regulatórios em diagnósticos assistidos por IA.
