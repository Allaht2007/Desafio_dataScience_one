# Análise de Desempenho - Lojas Alura Store

Este projeto contém um script de análise de dados em Python, utilizando a biblioteca pandas, para avaliar o desempenho de quatro lojas da rede Alura Store.

## Objetivo

O objetivo principal desta análise é examinar métricas de desempenho de quatro lojas com base em dados de vendas, incluindo:

<ul>

* Faturamento total

* Vendas por categoria de produto

* Avaliação média dos clientes

* Produtos mais e menos vendidos

* Custo médio do frete

</ul>
A análise visa fornecer insights para auxiliar na tomada de decisão estratégica, como a identificação de uma loja com desempenho inferior para uma potencial venda.

## Requisitos

Para executar este script, é necessário ter o Python instalado e a biblioteca pandas.

## Instalação

Você pode instalar a biblioteca pandas utilizando o pip:

```pip install pandas```


## Sobre a Análise

O script (.ipynb) realiza as seguintes etapas:



1. Importação de Dados: Carrega os dados de vendas de quatro arquivos CSV distintos, cada um representando uma loja.

2. Cálculo de Métricas:
<ul>

  * Soma o faturamento total (Preço) de cada loja.

  * Agrupa as vendas por Categoria do Produto e soma os valores.

  * Calcula a média da Avaliação da compra para cada loja.

  * Identifica os produtos mais e menos vendidos (com base na contagem de aparições) por loja.

  * Calcula o valor médio do Frete por loja.
</ul>

3. Visualização: Gera gráficos (pizza e barras) para comparar visualmente o desempenho das lojas nas métricas analisadas.

4. Relatório: Conclui com uma análise textual que sintetiza os resultados, sugerindo qual loja apresenta os piores índices para uma possível venda.
