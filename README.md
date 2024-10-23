# Análise Melhores pontos para Poços de Petróleo

## Descrição do Projeto
Este projeto tem como objetivo desenvolver um modelo que possa prever o melhor local para a perfuração de poços de petróleo.
Utilizando modelo de machine learning para poder prever o lucro de cada poço.

## Ferramentas e Bibliotecas Utilizadas
- Python: Linguagem principal utilizada para a análise.
- Pandas e Numpy: Biblioteca para manipulação e análise de dados.
- Sklearn: Biblioteca para construção de modelo de machine learning.
- Matplotlib.pyplot: Biblioteca para construção de gráficos

## Tabela
Para este projeto temos três conjuntos de dados, um para cada região de perfuração, e todos com as mesmas informções:
- id — identificador unívoco de poço de petróleo
- f0, f1, f2 — três características de pontos
- product — volume de reservas no poço de petróleo (milhares de barris).

## Condições:
- Apenas regressão linear deve ser usada para o treinamento do modelo.
- Ao explorar a região, um estudo de 500 pontos é realizado e os melhores 200 pontos são selecionados para calcular o lucro.
- O orçamento para o desenvolvimento de 200 poços de petróleo é 100 milhões de dólares.
- Um barril de petróleo bruto traz 4.5 dólares de receita. A receita de uma unidade de produto é 4.500 dólares (o volume de reservas está em milhares de barris).
- Depois de ter avaliado os riscos, mantenha apenas as regiões com o risco de perdas inferior a 2.5%. Entre aquelas que se enquadram no critério, você precisa selecionar a região com o lucro médio mais alto.
- **Os dados são sintéticos e não incluem nenhum detalhe de contratos ou características de poços.**

## Metodologia
**Análise Exploratória de Dados**
- Importar as bibliotecas necessárias
- Carregar e visualizar os dados

**Preparação do conjunto para o modelo**
- Identificação das festures e target do modelo
- Divisão dos conjuntos em treino, teste e validação

**Construindo e testando modelos**
- Regressão Linear
  - Treino
  - Teste
  - Métricas de avaliação
 
**Calculo de Lucro**
- Criação de uma função para o cálculo do lucro de cada poço de acordo
- Aplicação da técnica de bootstrapping

## Resultados
Após analisar todos os locais e postos selecionados, e levando em conta a qualidade do modelo de regressão que montamos, eu acrdito que a melhor região é a segunda. 
Pois o modelo é mais preciso que os demais e que por mais que apresente o menor lucro, é a que considero ter a menor chance de risco. 

## Aprendizados
- Análise de dados: interpretação e extração de insights valiosos a partir de grandes volumes de dados.
- Preparação do conjunto para aplicações em Machine Learning: separação do conjunto original em teste e treino, além da seleção das features e target do modelo.
- Funções: construção e aplicação de funções para simplificar o código.
- Regras de negócios: aplicação de regras de negócio para resolução de problemas.
- Técnica de bootstrapping: aplicação para construção de intervalos de confiança.
- Aplicação de modelos de Machine Learning: aplicação, seleção de hiperparâmetros, teste e avalição do modelo.
- Documentação de projetos: elaboração de documentação clara e detalhada para garantir que o projeto seja compreensível e replicável.
- Utilização de bibliotecas e ferramentas: aplicação prática de diversas bibliotecas e ferramentas do ecossistema Python.
- Tomada de decisões baseadas em dados: uso de insights derivados da análise de dados para orientar decisões estratégicas.
