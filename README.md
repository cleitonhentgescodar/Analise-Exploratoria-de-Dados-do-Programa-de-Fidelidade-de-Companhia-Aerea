# ✈️ Análise Exploratória e Modelagem Preditiva do Programa de Fidelidade de Companhia Aérea

Este projeto aplica técnicas de **Análise de Dados** e **Machine Learning** para investigar o comportamento de clientes em um **programa de fidelidade aérea**, avaliando o impacto de uma **campanha promocional de adesão**, padrões de engajamento e a **previsão de cancelamentos (churn)**.

O estudo combina **dados demográficos, histórico de cadastro e atividade de voos**, permitindo gerar insights estratégicos para **marketing, retenção e otimização de programas de milhagem**.

---

## 📊 Dataset

O projeto utiliza dois conjuntos de dados principais:

### 🗂 Customer Loyalty History
Informações cadastrais e demográficas dos membros:
- Loyalty Number
- Enrollment Year / Month
- Enrollment Type (Regular ou Promocional)
- Cancellation Year / Month
- Gender, Education, Salary, Marital Status
- City, Province

### ✈️ Customer Flight Activity
Atividade operacional dos clientes:
- Flights Booked
- Flights with Companions
- Total Flights
- Points Accumulated
- Points Redeemed

---

## 🎯 Objetivos

- Realizar **Análise Exploratória de Dados (EDA)**
- Avaliar o **impacto da campanha promocional nas adesões**
- Identificar **perfis demográficos mais engajados**
- Analisar padrões de uso do programa (voos e pontos)
- Detectar fatores associados ao **cancelamento (churn)**
- Construir **modelo preditivo de churn**
- Gerar **insights estratégicos orientados a negócio**

---

## ❓ Questões de Pesquisa

- A campanha aumentou significativamente o número de membros?
- Quais perfis de clientes apresentam maior engajamento?
- O comportamento de voo influencia a retenção?
- É possível prever cancelamentos usando Machine Learning?
- Quais variáveis são mais importantes para o churn?

---

## 🛠 Metodologia

### 🔹 Pré-processamento
- Limpeza de dados
- Tratamento de valores ausentes
- Junção das bases
- Conversão de datas
- Criação de variáveis derivadas

### 🔹 Análise Exploratória (EDA)
- Tendência temporal de adesões
- Comparações antes/durante/depois da campanha
- Distribuições de voos e pontos
- Segmentação demográfica
- Correlações entre variáveis

### 🔹 Engenharia de Features
- Identificação do período promocional
- Criação da variável alvo (Churn)
- Métricas agregadas de engajamento

### 🔹 Modelagem Preditiva
- Classificação binária (Stayed vs Cancelled)
- Random Forest Classifier
- Avaliação com:
  - Acurácia
  - Precisão
  - Recall
  - F1-score
- Importância das variáveis

---

## 📈 Principais Resultados

### ✅ Impacto da Campanha
- 971 novas adesões
- 141 cancelamentos
- +830 crescimento líquido

### 👥 Perfil dos Clientes
- Maior adesão em grandes centros urbanos
- Diferenças comportamentais entre grupos demográficos

### ✈️ Engajamento
- Aumento no número de reservas após a campanha
- Clientes mais ativos acumulam mais pontos

### 🤖 Modelo de Churn
- Acurácia ~ 95%
- Variáveis comportamentais mais relevantes que demográficas
- Possibilidade de retenção proativa

---

## 💡 Insights de Negócio

- Campanhas promocionais ampliam a base de clientes
- Segmentação geográfica melhora ações de marketing
- Baixa atividade de voo é indicativo de churn
- Modelos preditivos ajudam a reduzir cancelamentos
- Dados permitem decisões estratégicas baseadas em evidências

---

## 🧰 Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🚀 Próximos Passos

- Testar outros modelos (XGBoost, Logistic Regression)
- Balanceamento de classes (SMOTE)
- Segmentação de clientes (Clusterização)
- Dashboard interativo (Power BI/Streamlit)
- Deploy do modelo de churn

## 📌 Conclusão

Este projeto demonstra como Ciência de Dados aplicada ao setor aéreo pode gerar insights estratégicos, melhorar retenção de clientes e otimizar campanhas de fidelidade.

A combinação de EDA + Machine Learning transforma dados operacionais em vantagem competitiva orientada por dados.
