# Oracle-Next-Education--challenge-Analise-de-Dados

Alura Store - Análise de Desempenho das Lojas
Propósito da Análise
O propósito deste projeto é analisar o desempenho de quatro lojas, levando em consideração os seguintes aspectos:

**Faturamento total por loja**
**Categorias de produtos mais e menos vendidas.**
**Média das avaliações de clientes.**
**Produtos mais e menos vendidos.**
**Frete médio por loja.**


Com base nessas análises, o objetivo é fornecer informações sobre o desempenho de cada loja e identificar qual loja deve ser vendida e qual deve ser mantida.

Estrutura do Projeto
O projeto é estruturado da seguinte forma:


  - **Notebook principal com a análise dos dados.**

     challenge Analise de Dados.ipynb
  - **Pasta contendo os dados de entrada.**
   
      https://github.com/alura-es-cursos/challenge1-data-science/tree/main/base-de-dados-challenge-1
  - **Arquivo CSV com informações sobre as lojas.**
                                    
      lojas.csv                    
  - **Dependências do projeto.**
   
      requirements.txt 
  - **Este arquivo.**
   
      README.md                         

**Descrição dos Arquivos**

challenge Analise de Dados.ipynb: O notebook contém a análise completa, desde a leitura dos dados até a geração de gráficos e conclusões.

data/lojas.csv: Contém os dados utilizados para a análise.

requirements.txt: Lista as bibliotecas necessárias para executar o notebook, como pandas, matplotlib, seaborn.

Exemplos de Gráficos e Insights Obtidos
Durante a análise, foram gerados os seguintes gráficos e insights:

Faturamento por Loja
Um gráfico de barras foi gerado para mostrar o faturamento total de cada loja. A Loja 1 se destacou com o maior faturamento, seguida pela Loja 2, Loja 3 e Loja 4.

Categorias de Produtos Mais e Menos Vendidas
Gráficos de barras para cada loja ilustram as categorias mais e menos vendidas, permitindo uma visão clara sobre os produtos que geram mais receita e os que precisam de mais atenção.

Avaliação Média por Loja
Foi gerado um gráfico de linha representando a média de avaliações dos clientes por loja. A Loja 3 teve a maior média de avaliações.

Frete Médio por Loja
Um gráfico de linha também foi utilizado para comparar o frete médio entre as lojas. A Loja 4 teve o menor frete médio.

**Instruções para Executar o Notebook**

Este projeto foi desenvolvido e executado no Google Colab, facilitando a execução sem necessidade de configurações locais. Para rodar o notebook no Colab, siga os passos abaixo:

Executando no Google Colab
Clone o repositório:

Para clonar o repositório no seu ambiente local ou diretamente no Colab, execute no Colab:

python
Copiar
Editar
!git clone https://github.com/seu_usuario/Challenge-Analise-de-Dados.git
%cd Challenge-Analise-de-Dados
Abra o notebook no Google Colab:

Acesse o notebook diretamente pelo Google Colab carregando o arquivo Challenge_Analise_de_Dados.ipynb:

Clique aqui para abrir no Google Colab

Execute as células:

No Colab, basta executar as células do notebook para carregar os dados, realizar as análises e gerar os gráficos.

Executando Localmente (Opcional)
Caso prefira executar o notebook localmente:

Instale as dependências necessárias com o comando:

bash
Copiar
Editar
pip install -r requirements.txt
Abra o notebook no Jupyter:

bash
Copiar
Editar
jupyter notebook Challenge_Analise_de_Dados.ipynb
Execute as células do notebook para visualizar as análises e gráficos.

