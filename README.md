# mvp-analise-de-dados
MVP para o Sprint Análise de Dados e Boas Práticas da PUC-Rio

## Análise de Evasão e Sucesso Acadêmico

Este projeto tem como objetivo analisar fatores associados à evasão e ao sucesso acadêmico de estudantes do ensino superior, a partir de um conjunto de variáveis demográficas, socioeconômicas, institucionais e de desempenho acadêmico.

---

##  Dataset

Dataset utilizado:  
🔗 https://archive.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+success

A base foi disponibilizada via GitHub e utilizada no notebook por meio de link raw, garantindo reprodutibilidade.

---

## Objetivo

Investigar como diferentes características dos estudantes influenciam sua trajetória acadêmica, com foco em:

- Identificar padrões associados à evasão e ao sucesso
- Analisar o impacto do desempenho acadêmico inicial
- Explorar a influência de fatores socioeconômicos e institucionais

---

##  Perguntas de Pesquisa

- **[P1]** Qual é a relação entre o desempenho acadêmico nos primeiros semestres e o sucesso ou evasão dos estudantes?  
- **[P2]** Quais variáveis socioeconômicas e institucionais parecem mais associadas à evasão acadêmica?

---

## Metodologia

O projeto foi desenvolvido seguindo as etapas de análise de dados:

### 1. Preparação dos dados
- Carregamento do dataset via URL (GitHub raw)
- Verificação de tipos de dados
- Análise de valores faltantes e duplicados

### 2. Análise Exploratória de Dados (EDA)
- Estatísticas descritivas
- Distribuição da variável alvo (`Target`)
- Histogramas de variáveis numéricas
- Boxplots por categoria
- Mapa de correlação
- Gráfico de dispersão

### 3. Pré-processamento
- Conversão de variáveis categóricas
- One-hot encoding
- Padronização (StandardScaler)
- Normalização (MinMaxScaler)
- Discretização da idade

---

## Principais Resultados

- O desempenho acadêmico nos primeiros semestres mostrou forte associação com o desfecho dos estudantes.
- Estudantes com maiores notas e maior número de disciplinas aprovadas tendem a concluir o curso.
- A evasão está frequentemente associada a baixo desempenho acadêmico.
- Fatores socioeconômicos, como inadimplência e situação das mensalidades, também influenciam a permanência, embora de forma menos direta.

---

## Limitações

- A análise é baseada em associações, não sendo possível inferir causalidade.
- Algumas variáveis são categóricas codificadas numericamente, exigindo cuidado na interpretação.
- Não foram aplicados modelos preditivos neste trabalho.

---

## Trabalhos Futuros

- Aplicação de modelos de Machine Learning para previsão de evasão
- Seleção de atributos mais relevantes
- Análise de balanceamento de classes
- Exploração de técnicas mais avançadas de feature engineering

---

## Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📌 Estrutura do Projeto

- `notebook.ipynb` → análise completa  
- `data.csv` → dataset  
- `descricao_atributos.csv` → descrição das variáveis  

---

## 👩‍💻 Autora

Projeto desenvolvido como parte de estudo em Análise de Dados.
