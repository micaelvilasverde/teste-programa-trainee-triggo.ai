# Teste Técnico triggo.ai · Engenharia de Dados e DataOps

Sobre o Projeto
Este repositório apresenta a solução completa para o Teste Técnico do processo seletivo da triggo.ai para o Programa Trainee 2025 de Excelência em Engenharia de Dados e DataOps.

A análise foi conduzida sobre um conjunto de dados de e-commerce brasileiro com foco em:

Qualidade e profundidade da análise exploratória

Soluções de problemas de negócio com dados

Visualizações interativas e insights acionáveis

Uso eficiente de tecnologias de dados



🧱 Estrutura do Projeto
notebooks/
│   └── olist_analysis.ipynb
├── data/
│   ├── olist_customers_dataset.csv
│   ├── olist_orders_dataset.csv
│   ├── olist_order_items_dataset.csv
│   ├── olist_order_payments_dataset.csv
│   ├── olist_order_reviews_dataset.csv
│   ├── olist_products_dataset.csv
│   ├── olist_sellers_dataset.csv
│   ├── olist_geolocation_dataset.csv
│   └── product_category_name_translation.csv
├── images/
│   └── [gráficos gerados]
└── README.md



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

📊 Análises Realizadas
1. Evolução de Pedidos ao Longo do Tempo
Analisamos a quantidade de pedidos realizados ao longo do tempo para identificar tendências sazonais e crescimento do e-commerce.

2. Vendas por Estado
Utilizamos um mapa coroplético para visualizar o volume de vendas por estado brasileiro, identificando as regiões com maior faturamento.

3. Avaliações dos Clientes
Análise das avaliações dos clientes para entender a satisfação geral e identificar possíveis áreas de melhoria.

4. Tempo de Entrega
Estudo do tempo médio de entrega dos pedidos, destacando possíveis atrasos e eficiência logística.

5. Meios de Pagamento
Distribuição dos diferentes meios de pagamento utilizados pelos clientes, identificando preferências e tendências.

📌 Principais Insights
Regiões com Maior Faturamento: Os estados do Sudeste concentram a maior parte das vendas, destacando-se São Paulo e Rio de Janeiro.

Satisfação dos Clientes: A maioria das avaliações dos clientes é positiva, indicando uma boa experiência de compra.

Eficiência Logística: O tempo médio de entrega está dentro do esperado, com alguns casos de atrasos que merecem atenção.

Preferência por Cartão de Crédito: A maioria dos clientes opta por pagar com cartão de crédito, seguido por boleto bancário.


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



▶️ Como Executar
Acesse o Google Colab: (https://colab.research.google.com/drive/15wpZw6fB1rMkqLulfxxgYU6DaRapzUzr?usp=sharing) https://drive.google.com/drive/folders/1HMKzZ0W6STH_tFhnqBgi-G9oKWX7-2Ii?usp=sharing

Faça upload do notebook teste_triggo.ipynb e do olist_data.zip

Execute todas as células

Os gráficos serão exibidos no notebook



🔧 Melhorias Futuras
Uso de BigQuery ou Redshift para análise em escala

Deploy em um dashboard com Streamlit ou Power BI

Automatização com Airflow ou Dagster

Criação de um pipeline de dados real com transformação e ingestão

