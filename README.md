# Análise Temporal e Predições de Indicadores Econômicos do Banco Central

## Descrição do Projeto

Este projeto tem como objetivo capturar dados públicos referentes ao indicador de atividade econômica produzido pelo Banco Central, modelar esses dados em uma série temporal, criar um modelo de predição baseado em machine learning e visualizar os resultados históricos e preditivos no mesmo gráfico.

A fonte de dados utilizada pode ser acessada através do [Banco Central API](https://api.bcb.gov.br/dados/serie/bcdata.sgs.24363/dados?formato=json).

## Objetivos
<ul>
  <li><strong>Extração de Dados:</strong> Leitura automática dos dados diretamente do endereço fornecido sem necessidade de download manual.</li>
  <li><strong>Modelagem de Dados:</strong> Construção de uma base de dados na forma de série temporal.</li>
  <li><strong>Predição:</strong> Desenvolvimento de um modelo de machine learning para prever futuras atividades econômicas.</li>
  <li><strong>Visualização de Resultados:</strong> Geração de um gráfico que inclui:
    <ul>
      <li>Série temporal histórica dos últimos 5 anos.</li>
      <li>Predição para os próximos 6 períodos.</li>
      <li>Limites superiores e inferiores das previsões.</li>
    </ul>
  </li>
</ul>

## Estrutura do Dados

Os dados são compostos por:
 <li><strong>Data:</strong> Data da medição.</li>
  <li><strong>Valor:</strong> Índice de confiança do consumidor.</li>


   
