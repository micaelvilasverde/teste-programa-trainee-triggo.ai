# Teste Técnico triggo.ai · Engenharia de Dados e DataOps

Sobre o Projeto
Este repositório apresenta a solução completa para o Teste Técnico do processo seletivo da triggo.ai para o Programa Trainee 2025 de Excelência em Engenharia de Dados e DataOps.

A análise foi conduzida sobre um conjunto de dados de e-commerce brasileiro com foco em:

Qualidade e profundidade da análise exploratória

Soluções de problemas de negócio com dados

Visualizações interativas e insights acionáveis

Uso eficiente de tecnologias de dados



🧱 Estrutura do Projeto
bash
Copiar
Editar
📁 projeto-triggo
│
├── teste_triggo.ipynb          # Notebook principal com todas as análises
├── README.md                   # Este arquivo
├── /data                       # Dados extraídos do zip da Olist
│   ├── olist_customers_dataset.csv
│   ├── olist_orders_dataset.csv
│   ├── ...
└── /imagens                    # Gráficos e visualizações salvos



🛠️ Tecnologias e Bibliotecas
Python 3.11+

Google Colab

Pandas e NumPy – Manipulação de dados

Matplotlib e Seaborn – Visualizações

Scikit-learn – Modelos e clusterização

Plotly (opcional) – Visualizações interativas




📊 Etapas da Solução

📁 1. Importação e Organização dos Dados
Extração automática do zip

Leitura e padronização de todos os .csv

Criação de chaves de relacionamento entre as tabelas

🔍 2. Análise Exploratória
Distribuição de clientes por estado e cidade

Evolução mensal das vendas

Formas de pagamento e sua popularidade

Entregas por região via heatmap

Avaliação dos produtos (review score)

Categorias mais vendidas

🚀 3. Solução de Problemas de Negócio
Relação entre frete e nota de avaliação

Predição de atraso com regressão logística (modelo simples)

Clusterização de clientes com KMeans (perfil de consumo)

📈 4. Visualizações Interativas
Evolução de vendas mensais

Heatmap de entregas por estado

Score de avaliações por categoria

Ranking das formas de pagamento

Gráficos de dispersão para detecção de outliers



✅ Resultados e Insights
Estados do Sudeste concentram a maioria das vendas

Cartão de crédito é a forma de pagamento dominante

Fretes mais caros tendem a avaliações piores

Modelos simples conseguem prever atrasos com acurácia > 70%

Clientes podem ser agrupados em 3 perfis distintos de comportamento



▶️ Como Executar
Acesse o Google Colab: https://colab.research.google.com/

Faça upload do notebook teste_triggo.ipynb e do olist_data.zip

Execute todas as células

Os gráficos serão exibidos no notebook



🔧 Melhorias Futuras
Uso de BigQuery ou Redshift para análise em escala

Deploy em um dashboard com Streamlit ou Power BI

Automatização com Airflow ou Dagster

Criação de um pipeline de dados real com transformação e ingestão

