[![author](https://img.shields.io/badge/author-jaomarcelofc-red.svg)](https://www.linkedin.com/in/joao-marcelo-fonseca-cunha) [![](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-365/)

# Data Science Aplicada em Logística com Spark SQL

# Objetivo
O objetivo deste projeto é analisar um conjunto de dados de uma transportadora responsável por entrega de produtos. Diversos veículos realizam diversas entregas em diferentes horários do dia. Usando Spark SQL vamos extrair insights e compreender como está a performance da logística de entrega da empresa.

<p align="center">
  <img src= "imagens/sparksql.jpg"width=50% >
</p>

As soluções para cada pergunta de negócio são apresentadas em Linguagem SQL e com o uso de funções do Spark SQL. Temas como agregação, funções Window e parse de data também são abordados.

# Definição do problema e fonte de dados

Uma transportadora possui diversos veículos que são usados para entregas. Cada veículo realiza diversas entregas por dia e o horário exato de cada entrega é registrado. A empresa tenta otimizar o percurso de cada veículo fazendo com que um mesmo veículo faça todas as entregas em cada região, reduzindo assim o tempo entre uma entrega e outra. Os dados usados neste trabalho são fictícios e o dataset tem 3 colunas: id do veículo, a entrega que foi realiza e o horário. Usando Spark SQL faremos uma série de análises nos dados a fim de verificar como está a performance da logística de entrega da empresa.
