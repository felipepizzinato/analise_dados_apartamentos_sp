# 📊 Análise de Preços de Imóveis em São Paulo - Power BI & Python  

## 📌 Sobre o Projeto  
Este projeto tem como objetivo analisar os preços de apartamentos na cidade de São Paulo, utilizando **Python** para a extração, limpeza e análise exploratória dos dados (EDA) e **Power BI** para a construção de um dashboard interativo.  

Os dados foram coletados por meio de **Web Scraping** e passaram por um **processo completo de tratamento**, incluindo a remoção de outliers, padronização de nomes e criação de novas métricas.  

## 🚀 Tecnologias Utilizadas  
- ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)  
- ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)  
- ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)  

  
## 🔍 Processamento dos Dados com Python  
### 📌 Passos realizados:  
✅ **Importação e Consolidação dos Dados** 
- Dois datasets distintos foram unificados e colunas desnecessárias foram removidas
  
✅ **Padronização das Informações**
- Separação de endereços em rua, bairro e cidade
- Conversão de tipos de dados 
-  e criação de colunas derivadas (ano de criação do anúncio)
  
✅ **Limpeza dos Dados**
- Remoção de valores nulos, registros duplicados e cidades que não são de estado de São Paulo
- Normalização dos nomes de bairros

✅ **Criação de Métricas**
- Cálculo do valor do m² por bairro e criar uma coluna
- Estatísticas como média valor do m2 por bairro , desvio padrão (histograma e bloxsplot)

✅ **Tratamento de Outliers**
- Remoção de outliers extremos em colunas como preço, área, quantidade de quartos, banheiros e vagas de garagem
  
✅ **Exportação do Dataset Tratado**
- Sados salvos em um arquivo CSV para uso no Power BI  

## 📊 Visualização dos Dados no Power BI  
✅ **Preço médio do m² no estado de São Paulo**  
✅ **Média de quartos, banheiros e vagas de estacionamento** 
✅ **Correlação entre área e preço**  
✅ **Evolução dos preços ao longo do tempo**  
✅ **Top 10 bairros mais caros e mais baratos**  
✅ **Quantidade de imóveis por bairro**  
✅ **Distribuição geográfica dos preços por cidade**  
✅ **Distribuição geográfica da quantidade de imóvel por cidade**  



## 📂 Estrutura do Projeto  
- 📁 `data/` → Contém o dataset tratado  
- 📁 `notebooks/` → Scripts Python usados na análise
## 📊 Dashboard Interativo  
🔗 **Acesse o Dashboard no Power BI:** [Clique aqui](https://app.powerbi.com/view?r=eyJrIjoiMmMxMDAzNGItZWU0NC00OTcwLWIwMGItMzZlM2ViYTdmNzI1IiwidCI6IjExZGJiZmUyLTg5YjgtNDU0OS1iZTEwLWNlYzM2NGU1OTU1MSIsImMiOjR9)  

## 📢 Conclusões e Insights 
📌 A maioria dos bairros tem um valor/m² entre R$ 5.000 e R$ 15.000  
📌 Os bairros mais caros apresentam um valor/m² superior a R$ 30.000   
📌 Há forte correlação entre área e preço, mas algumas exceções indicam regiões supervalorizadas   
📌 A distribuição de imóveis não é homogênea entre bairros, havendo concentração em certas regiões    



