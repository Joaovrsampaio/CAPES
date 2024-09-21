# ANÁLISE DE DADOS SOBRE DISTRIBUIÇÃO DE BOLSAS DE POS GRADUAÇÃO CAPES NO BRASIL 1995-2023

## PARA UMA MELHOR VIZUALIZAÇÃO ONLINE DAS ANÁLISES O NOTEBOOK TAMBÉM ESTÁ DISPONÍVEL NO MEU KAGGLE QUE SUPORTA O TAMANHO DO NOTEBOOK E APRESENTA OS GRÁFICOS E MAPAS:
disponível no link: https://www.kaggle.com/code/joovictorsampaio/an-lise-capes

## Descrição
O projeto tem como foco analisar a concessão de bolsas de mestrado e doutorado pela CAPES entre 1995 e 2023. Para isso, foi realizada uma preparação do banco de dados demonstrada no notebook capes_preparacao e após essa preparação dos dados para deixar de formar mais organizada e padronizada foi feita uma análise detalhada dos dados no notebook analise_capes com o objetivo de compreender o comportamento da pós-graduação no Brasil ao longo desse período. A investigação busca entender a evolução no número de bolsas concedidas, o crescimento dos programas, a média de alunos por programa, e explorar períodos marcados por grandes mudanças. Também foi feita uma análise da distribuição das Instituições de Ensino Superior (IES) pelo Brasil, identificando as principais ao longo dos anos, além de examinar as grandes áreas com maior número de programas oferecidos.

O projeto também contempla uma análise espacial da distribuição dos tipos de status jurídico das IES pelo país, com foco nas instituições federais, estaduais, municipais e particulares. Por fim, foi realizada uma investigação da distribuição espacial do número de programas de pós-graduação. O objetivo central é verificar como a oferta de programas se distribui pelo território brasileiro, identificando as regiões com maior concentração e como essa oferta evoluiu ao longo do tempo.

As ferramentas utilizadas no projeto foram:

- Python como linguagem
- Pandas e Numpy para a manipulação dos dados
- Jupyter Notebook para criação do código
- Plotly e suas ferramentas e pyplot para a plotagem dos gráficos e mapas
- Geopandas e Json para a manipulação dos dados geográficos
- ipywidgets para a interação do código com o usuário
- Tabulate para a criação de tabelas
- Limpeza e preparação de um banco de dados como o unicode


## Estrutura do Repositório CAPES

- capes_dados.rar: É um arquivo zipado com as duas bases utilizadas, o arquivo dados.xlsx é o arquivo bruto utilizado para fazer a preparação do dataset, e o arquivo capes.csv é o utilizado na análise criado apartir da manipulação do dados.xlsx.
- capes_prepração: É o notebook de preparação dos dados brutos para a criação do capes.csv.
- analise_capes: É o notebook de análise, é nesse notebook que estão as análises do projeto, tal como os gráficos, mapas e tabelas geradas, por motivo de ter um tamnho que não é aceito pelo github, foi necessário utilizar o git Large File Storage para fazer o push desse notebook e por conta disso ele não está disponivél para vizualização
- brasil_geo.json: É o shape file utilizado para criar os mapas dos estados brasilieros.

## FONTES
- A fonte primária: https://geocapes.capes.gov.br/geocapes/ plataforma da CAPES que disponibiliza todos esses dados de pós-graduação no Brasil.
- Fonte do Shapefile: https://www.kaggle.com/datasets/thiagobodruk/brazil-geojson/code
- Fonte dos dados da análise: Os dados preparados por mim nesse projeto também está disponivél no meu kaggle como um dataset público https://www.kaggle.com/datasets/joovictorsampaio/capes-info


