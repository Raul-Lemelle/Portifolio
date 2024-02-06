# Projeto de Previsão de Popularidade de Músicas usando Machine Learning

Este projeto tem como objetivo desenvolver um modelo de machine learning capaz de prever a popularidade de músicas com base em diversas características musicais. A popularidade é uma métrica crucial na indústria da música, impactando o sucesso de artistas, plataformas de streaming e profissionais do setor.

## Problema

O aumento nas opções de streaming de música e a diversidade de preferências dos ouvintes tornam desafiadora a compreensão e previsão da popularidade de uma música. Este projeto visa resolver esse problema, explorando como as características musicais, como acústica, dancabilidade, energia, instrumentalidade, entre outras, contribuem para a popularidade de uma música.

## Justificativa

- **Otimização de Catálogo:** Compreender as características que influenciam a popularidade permite que as plataformas de streaming otimizem seus catálogos, promovendo músicas mais propensas a atrair uma audiência mais ampla.

- **Apoio a Artistas:** Artistas e gravadoras podem se beneficiar ao entender quais características musicais estão associadas a maior popularidade, orientando suas decisões de produção e promoção.

- **Experiência do Usuário:** Plataformas de streaming podem melhorar a experiência do usuário ao recomendar músicas mais alinhadas aos gostos individuais dos ouvintes.

## Metodologia

- **Análise de Dados:** Utilizamos um conjunto de dados contendo informações sobre músicas, incluindo artistas, características musicais e a variável alvo, "popularidade".

- **Machine Learning:** Implementamos um modelo de regressão (Random Forest Regressor neste exemplo) para prever a popularidade com base nas características fornecidas.

- **Avaliação do Modelo:** Avaliamos o desempenho do modelo utilizando a métrica de Erro Quadrático Médio (Mean Squared Error) e visualizamos a importância relativa das características.

## Como Utilizar

1. **Requisitos:** Certifique-se de ter as bibliotecas necessárias instaladas (veja o arquivo `requirements.txt`).
   
2. **Fonte de Dados:** Link: "https://www.kaggle.com/datasets/vicsuperman/prediction-of-music-genre/data".

3. **Treinamento do Modelo:** Execute o script Python para treinar o modelo.

4. **Ajuste e Otimização:** Considere ajustar hiperparâmetros e otimizar o modelo conforme necessário.

5. **Avaliação:** Analise as métricas de desempenho e visualize a importância das características.

## Resultados Esperados

- Melhoria na curadoria de playlists e sugestões personalizadas para os usuários.

- Este projeto visa contribuir para uma indústria da música mais eficiente e alinhada com as preferências dos ouvintes.

Sinta-se à vontade para explorar, ajustar e expandir este projeto para atender às suas necessidades específicas.
