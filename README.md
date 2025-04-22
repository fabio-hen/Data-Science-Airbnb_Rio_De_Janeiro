# 🏠 Análise de Dados do Airbnb – Rio de Janeiro

Este projeto apresenta uma análise exploratória dos dados de acomodações do Airbnb na cidade do **Rio de Janeiro**, utilizando Python e bibliotecas de ciência de dados como Pandas, Matplotlib e Seaborn. O objetivo foi extrair **insights relevantes sobre o mercado de hospedagem alternativa**, como distribuição de preços, tipos de imóveis mais comuns e concentração geográfica dos anúncios.

 > 🔗 **Artigo completo publicado no Medium**: [clique aqui para ler](https://medium.com/@fabio.he/an%C3%A1lise-de-dados-do-airbnb-rio-de-janeiro-404ab7af6c87)

---

## 📁 Sobre os Dados

Os dados utilizados foram obtidos na plataforma [Inside Airbnb](http://insideairbnb.com), que oferece datasets públicos de diversas cidades ao redor do mundo.

- 📌 Cidade: Rio de Janeiro – RJ  
- 📅 Data de referência da base: **27/12/2024**  
- 📥 Download realizado em: **14/04/2025**  
- 📄 Arquivo utilizado: `listings.csv` (versão resumida)

Essa base contém as principais métricas de cada anúncio, ideal para visualizações e análises iniciais.

---

## 📊 Objetivos da Análise

- Compreender a distribuição dos tipos de imóveis anunciados
- Analisar a variação dos preços e identificar **outliers**
- Explorar a distribuição geográfica das propriedades
- Verificar correlações entre variáveis como preço, número de noites e reviews
- Obter insights para **viajantes, investidores e gestores públicos**

---

## ⚙️ Tecnologias Utilizadas

- Python 3
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
- NumPy

---

## 📌 Principais Insights

- Cerca de **80%** das acomodações são imóveis inteiros (apartamentos/casas)
- O preço médio é de **R$ 1.227**, com grande variação (de R$ 33 a R$ 500.000)
- A maioria dos imóveis está concentrada em bairros turísticos como **Copacabana, Ipanema e Barra da Tijuca**
- Identificou-se uma fraca correlação entre preço e noites mínimas, sugerindo que outros fatores têm mais impacto no valor final

---

## 🧼 Limpeza e Pré-Processamento

- Remoção de outliers com base no IQR (Intervalo Interquartil)
- Exclusão de colunas irrelevantes ou com muitos valores ausentes
- Reajuste nas distribuições para melhorar a visualização e interpretação

---

## 📂 Como Rodar o Projeto

1. Clone este repositório
2. Instale os pacotes necessários:
   ```bash
   pip install -r requirements.txt
3. Execute o notebook airbnb_analysis_rio.ipynb em um ambiente Jupyter

---

## ✉️ Contato
Projeto desenvolvido por Fábio Henrique de Almeida
> 🔗 Conecte-se comigo no [LinkedIn](https://www.linkedin.com/in/fhalmeida/)
