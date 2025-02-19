# 🛒 Análise de Métricas e Clusterização de Clientes em E-commerce

## 📌 Contexto
Uma empresa de e-commerce deseja entender melhor o comportamento de seus clientes para personalizar campanhas de marketing e otimizar suas estratégias comerciais.

Para isso, a empresa disponibilizou um conjunto de dados em formato CSV contendo informações sobre clientes, produtos e transações realizadas entre 2010 e 2011.

O objetivo deste projeto é:
✅ Identificar perfis de clientes com base no comportamento de compra  
✅ Detectar padrões e características em comum entre os clientes  
✅ Realizar clusterização para segmentação da base de clientes  
✅ Gerar insights para personalização de campanhas de marketing  

## 📂 Sobre os Dados
A base de dados contém as seguintes variáveis:  

InvoiceNo: Identificação da transação   
StockCode: Código de estoque do produto  
Description: Descrição do produto  
Quantity: Quantidade de produtos por transação  
InvoiceDate: Data da transação  
UnitPrice: Preço unitário do produto  
CustomerID: Identificação do cliente  
Country: País de origem da transação  

## 🔍 Etapas do Projeto
### 1️⃣ Análise Exploratória dos Dados (EDA - Exploratory Data Analysis) 📊
Visualização e estatísticas gerais  
Identificação de padrões iniciais  

### 2️⃣ Pré-processamento dos Dados 🛠
Tratamento de valores nulos e duplicados  
Ajustando tipos de variáveis  
Criando nova feature (Total_Price)  
Removendo valores menores ou iguais a zero para 'Quantity' e 'UnitPrice'  
Removendo outliers  
Criando as métricas RFV  
Padronização e normalização de variáveis  

### 3️⃣ Seleção do Algoritmo de Clusterização 🤖
K-Means  
Escolha do modelo mais adequado para segmentação  

### 4️⃣ Análise dos Clusters Obtidos 🔍
Interpretação dos perfis gerados  
Comparação dos grupos identificados  

### 5️⃣ Interpretação dos Resultados 🎯
Geração de insights estratégicos para campanhas de marketing  

## 🛠 Tecnologias Utilizadas
### Manipulação e Análise de Dados:
pandas → Leitura e manipulação de dados  
missingno → Visualização de valores ausentes  

### Visualização de Dados:
seaborn e matplotlib.pyplot → Gráficos e análises exploratórias  
plotly.express → Visualizações interativas  

### Pré-processamento e Transformação de Dados:
scale (do sklearn.preprocessing) → Normalização dos dados  
PowerTransformer → Transformação estatística para melhor distribuição dos dados  

### Clusterização:
KMeans (do sklearn.cluster) → Algoritmo de agrupamento  
yellowbrick.cluster → Visualização de métricas para otimização dos clusters  

### Avaliação dos Clusters:
kelbow_visualizer → Determinação do número ideal de clusters com o método do cotovelo  
SilhouetteVisualizer e silhouette_score → Avaliação da coesão dos clusters  
davies_bouldin_score e calinski_harabasz_score → Métricas de qualidade dos agrupamentos  

## 📬 Contato
Se tiver dúvidas ou sugestões, entre em contato!
