# alura-telecomx2
Challenge Alura - Telecom X 2

## 📌 Descrição do Projeto
Este projeto tem como objetivo analisar e prever a **evasão de clientes** de uma empresa de telecomunicações utilizando técnicas de **Machine Learning**. A análise foca em identificar os principais fatores que influenciam o cancelamento de planos e propor estratégias de retenção.

## 💻 Tecnologias Utilizadas
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn (Regressão Logística, KNN, Random Forest, métricas)
- Imbalanced-learn (SMOTE)

## 🛠 Pré-processamento
- Transformação de variáveis categóricas em **numéricas** via **One-Hot Encoding**.
- Normalização de variáveis numéricas para modelos sensíveis à escala.
- Divisão da base em **treino (80%) e teste (20%)**.
- Aplicação de técnicas de balanceamento como **SMOTE** para lidar com desbalanceamento.

## 📊 Análise Exploratória
- Visualização da **matriz de correlação** para identificar relações entre variáveis.
- Avaliação de como variáveis específicas se relacionam com a evasão, como:
  - Tempo de contrato × Evasão
  - Total gasto × Evasão
- Criação de gráficos como **boxplots** e **scatter plots** para identificar padrões.

## 🤖 Modelagem
- Criação de modelos de **Regressão Logística** e **Random Forest**.
- Justificativa:
  - Regressão Logística: interpretável, sensível à escala, identifica importância das variáveis.
  - Random Forest: robusto, não sensível à escala, captura relações não lineares.

## 📈 Avaliação de Modelos
- Métricas utilizadas:
  - Acurácia
  - Precisão
  - Recall
  - F1-score
  - Matriz de Confusão
- Análise crítica do desempenho e possíveis ajustes para overfitting ou underfitting.

## 🔑 Principais Insights
- Variáveis mais relevantes para evasão: **Tempo de contrato, Total gasto, Tipo de contrato, Método de pagamento e Perfil senior**.
- Contratos longos reduzem evasão; clientes com gastos altos podem demandar atenção; métodos de pagamento automáticos e campanhas segmentadas para clientes senior ajudam na retenção.

## 📌 Estratégias de Retenção
- Incentivar contratos mais longos.
- Oferecer benefícios para clientes de alto valor.
- Incentivar métodos de pagamento automáticos.
- Desenvolver campanhas segmentadas para clientes senior.

## 🚀 Como Executar
1. Clone o repositório:
```bash
git clone https://github.com/SEU-USUARIO/TelecomX.git
