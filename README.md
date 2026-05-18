# 👋 Olá, sou Eduardo Matos!

### Cientista de Dados | Machine Learning | Python | SQL | FastAPI

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Eduardo_Matos-blue?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/matos-eduardo)
[![Email](https://img.shields.io/badge/Email-eduardomatos2399@gmail.com-red?style=for-the-badge&logo=gmail)](mailto:eduardomatos2399@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-GitHub-black?style=for-the-badge&logo=github)](https://github.com/edudatalytics)

---

## 🎯 Sobre Mim

Cientista de Dados com projetos end-to-end em Machine Learning — desde a exploração e preparação dos dados até modelagem, validação e deploy em produção. Foco em transformar dados em decisões de negócio mensuráveis.

- 🔭 Atualmente: desenvolvendo soluções de ML com deploy via API REST e Streamlit
- 🌱 Aprendendo: MLOps, Cloud (AWS/GCP), Deep Learning
- 💼 Buscando: primeira oportunidade formal como Cientista de Dados Júnior
- 🎓 Formação: EBAC — Profissão Cientista de Dados | ADS — Unicesumar (em andamento)
- 📍 Localização: Formiga, MG — Brasil (disponível para remoto)

---

## 🚀 Projetos em Destaque

### 🔒 [Detecção de Fraudes em Cartão de Crédito](https://github.com/edudatalytics/credit-card-fraud-detection)

Pipeline completo de ML para detectar transações fraudulentas em dataset altamente desbalanceado (284.807 transações, 0.17% fraudes).

| Métrica | Resultado |
|--------|-----------|
| ROC-AUC | **97,7%** |
| Recall | **82,7%** |
| Precision | **81,8%** |
| Economia estimada | **R$ 80.820** |
| ROI | **15:1** |

**Stack:** `Python` `Scikit-learn` `Random Forest` `XGBoost` `Streamlit` `MLflow` `SMOTE`

**Destaques:** Tratamento de desbalanceamento, otimização de threshold, deploy interativo em produção

---

### 📈 [Previsão de Receita Mensal — Olist E-commerce](https://github.com/edudatalytics/olist-revenue-forecast)

Pipeline end-to-end para previsão de receita mensal de e-commerce brasileiro: SQL → EDA → ML → API REST.

| Métrica | Resultado |
|--------|-----------|
| MAPE | **3,9%** (excelente para previsão de receita) |
| MAE | **R$ 41.281** |
| Melhor modelo | **Regressão Linear** |

**Stack:** `Python` `Pandas` `Scikit-learn` `SQLite` `FastAPI` `Matplotlib` `Seaborn`

**Destaques:** ABT construída via SQL com joins em 9 tabelas, EDA com identificação de sazonalidade e Black Friday, deploy via API REST com FastAPI

---

### 😴 [Sistema de Detecção de Sonolência](https://github.com/edudatalytics/projeto-sonolencia)

Sistema de visão computacional em tempo real que monitora motoristas detectando sonolência e bocejo via webcam, com alertas visuais, sonoros e dashboard de análise.

| Métrica | Resultado |
|--------|-----------|
| EAR limiar | **0.22** (fechamento dos olhos) |
| MAR limiar | **0.60** (detecção de bocejo) |
| Tempo de resposta | **1.5s** até o alerta |
| Log de eventos | **CSV automático** com timestamp |

**Stack:** `Python` `OpenCV` `MediaPipe` `NumPy` `Pygame` `Pandas` `Matplotlib`

**Destaques:** Cálculo de EAR e MAR em tempo real, alertas sonoros com .mp3 independentes por tipo, log automático de eventos e dashboard de análise com 4 gráficos

---

### 🗄️ [Pipeline ETL em SQL — Análise de Engajamento de Clientes](https://github.com/edudatalytics/sql-analise-engajamento-clientes)

Pipeline ETL completo em SQL puro para transformar dados brutos de transações em features analíticas prontas para Machine Learning.

**Destaques:**
- 9 CTEs encadeadas processando múltiplas tabelas
- Window Functions: ROW_NUMBER(), PARTITION BY para ranking complexo
- 30+ features temporais multi-período (7, 14, 28, 56 dias)
- Agregações de recência, frequência e produtos preferidos

**Stack:** `SQL` `SQLite` `Window Functions` `CTEs` `ETL` `Feature Engineering`

---

### 🔍 [Redução de Dimensionalidade em Imagens](https://github.com/edudatalytics/dimensionality-reduction-images)

Pipeline de pré-processamento de imagens implementado em Python puro — sem OpenCV ou Scikit-image — demonstrando os fundamentos de conversão RGB → Escala de Cinza → Binarização.

**Destaques:**
- Fórmula de luminância perceptual (padrão ITU-R BT.601)
- Binarização com threshold fixo
- Redução de dimensionalidade de 66% (RGB → Cinza)
- Aplicações: pré-processamento para CNNs, OCR, detecção de bordas

**Stack:** `Python` `PIL` `NumPy` `Matplotlib`

---

## 🛠️ Stack Técnico

### Linguagens
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

### Machine Learning & Data Science
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=for-the-badge)

### Visão Computacional
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=for-the-badge)

### Deploy & MLOps
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### Visualização
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

---

## 📊 Métricas Consolidadas dos Projetos

| Projeto | Métrica Principal | Impacto de Negócio |
|---------|------------------|-------------------|
| 🔒 Detecção de Fraude | ROC-AUC 97,7% | Economia estimada R$ 80.820 |
| 📈 Previsão de Receita Olist | MAPE 3,9% | Pipeline SQL → ML → API REST |
| 😴 Detecção de Sonolência | EAR + MAR em tempo real | Alertas visuais + sonoros + dashboard |
| 🗄️ Pipeline ETL SQL | 30+ features temporais | 9 CTEs encadeadas |
| 🔍 Redução de Dimensionalidade | Redução 66% | Pré-processamento para CNNs |

---

## 🎓 Formação & Certificações

- 🎓 **Análise e Desenvolvimento de Sistemas** — Unicesumar (2026 — em andamento)
- 🎓 **Profissão: Cientista de Dados** — EBAC (2023–2024)
- 📊 **Power BI para Business Intelligence** — EBAC (2024)
- 🤖 **Bootcamp Bradesco Dev Machine Learning** — DIO (2026)

---

## 📫 Contato

**Aberto a oportunidades remotas como Cientista de Dados Júnior ou Analista de Dados.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/matos-eduardo)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:eduardomatos2399@gmail.com)

📧 eduardomatos2399@gmail.com
📍 Formiga, MG — Brasil (remoto disponível)
