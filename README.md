# PROJETO-APLICADO-ANALISE-PREDITIVA

PROJETO APLICADO: ANÁLISE PREDITIVA E VANTAGEM COMPETITIVA
Professor: Sergio Monteiro

Trabalho 2 (70%) - Análise preditiva e otimização de escolha de ações
Aluno: Sóren do Prado Lopes Matrícula: 202208892426

Curso: MBA em BI & Data Science Campus e Turno: Barra/Noite

Descrição:
Este trabalho tem como objetivo construir uma aplicação Python utilizando recursos de aprendizado de máquina para prever valores de 10 ações (livre escolha) e utilizar os valores preditos em uma data futura específica, aplicando-os em uma função de otimização que escolherá apenas 3 ações para investimento de forma a maximizar o retorno do investimento.




Neste script, aplicamos o Knapsack Problem (Problema da Mochila) para selecionar as 3 melhores ações do ponto de vista lucrativo a partir de uma lista de ações pré-selecionadas. Utilizamos a biblioteca yfinance para obter dados históricos de fechamento das ações nos últimos 2 anos. Em seguida, calculamos a variação percentual diária das ações e aplicamos o Knapsack Problem para identificar as ações que maximizam o lucro, considerando a capacidade da "mochila" como 3.

As etapas do script são as seguintes:

Importar as bibliotecas necessárias e definir a função para resolver o Knapsack Problem.
Definir a lista de ações e o período de tempo para análise.
Obter os dados históricos de fechamento das ações utilizando a biblioteca yfinance.
Calcular a variação percentual diária das ações.
Aplicar o Knapsack Problem para encontrar as 3 melhores ações em termos de lucro.
Visualizar o desempenho das ações selecionadas em um gráfico.
O script fornece uma abordagem simplificada para selecionar ações com base em dados históricos e não garante sucesso no day trading. Para análises mais avançadas e completas, técnicas de aprendizado de máquina, análise de sentimento e análise técnica são aconselháveis. O Knapsack Problem usado neste script não é uma abordagem comum para selecionar ações, mas foi aplicado conforme a solicitação do usuário.
