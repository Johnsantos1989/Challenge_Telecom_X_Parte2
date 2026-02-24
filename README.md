# 📌 Challenge_Telecom_X_Parte2  
## TelecomX – Previsão de Churn (Parte 2)

### 📖 Sobre o Projeto
Este projeto é a segunda etapa do desafio **TelecomX**, dando continuidade ao tratamento e à análise exploratória realizados na Parte 1.  
Nesta fase, o foco foi a **modelagem preditiva**, com o objetivo de identificar clientes com maior risco de evasão (*churn*) e propor estratégias orientadas por dados para retenção.  

O projeto transforma insights descritivos da Parte 1 em soluções preditivas aplicáveis ao negócio.

---

### 🎯 Objetivos
- Construir modelos de Machine Learning para prever churn  
- Comparar diferentes algoritmos de classificação  
- Avaliar desempenho utilizando métricas adequadas  
- Identificar variáveis mais relevantes para evasão  
- Propor estratégias de retenção baseadas em dados  

---

### 📊 Etapas do Projeto
**1️⃣ Preparação dos Dados**  
- Tratamento de valores inconsistentes  
- Encoding de variáveis categóricas  
- Análise de correlação  
- Divisão em treino e teste (80/20)  

**2️⃣ Modelagem Preditiva**  
Modelos desenvolvidos:  
- Regressão Logística  
- Random Forest  

A normalização foi aplicada conforme necessário, considerando as características de cada algoritmo.  

**3️⃣ Avaliação dos Modelos**  
Métricas utilizadas:  
- Acurácia  
- Precisão  
- Recall  
- F1-score  
- Matriz de confusão  

📌 **Resultados:**  
- **Random Forest** apresentou melhor desempenho, capturando padrões não lineares e proporcionando maior generalização.  
- **Regressão Logística** complementou a análise, permitindo interpretação direta dos coeficientes e influência das variáveis.  

---

### 🔎 Principais Variáveis Relacionadas ao Churn
- `customer_tenure` (tempo de permanência)  
- `account_Charges_Total` (valor total gasto)  
- `account_Charges_Monthly` (valor mensal)  
- Tipo de contrato  
- Método de pagamento  

➡️ Clientes com menor tempo de contrato e contratos mensais apresentam maior probabilidade de churn.  

---

### 💡 Recomendações Estratégicas
- Implementar ações de retenção nos primeiros meses de contrato  
- Incentivar contratos de longo prazo  
- Monitorar clientes com alto risco predito  
- Estimular métodos de pagamento automáticos  
- Integrar o modelo como ferramenta de apoio à decisão  

---

### 🛠️ Tecnologias Utilizadas
- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Scikit-learn  

---

### 📌 Conclusão
Ao integrar análise exploratória e modelagem preditiva, foi possível transformar dados em **insights estratégicos** e propor ações concretas para redução da evasão.  

Este projeto demonstra a aplicação prática de técnicas de Machine Learning para resolver problemas reais de negócio, com foco em **retenção de clientes e tomada de decisão orientada por dados**.  

---

### 🔗 Projeto Relacionado
📎 Parte 1 – Análise Exploratória e Tratamento de Dados  
*https://github.com/Johnsantos1989/Challenge-Telecom-X*  

---

### 👤 Autor
**John Lenon Nogueira**  
Data Science | Machine Learning | Análise de Dados  

---

### 🚀 Resultado Final
Este case consolida:  
- Análise exploratória  
- Engenharia de atributos  
- Modelagem preditiva  
- Interpretação de modelos  
- Aplicação estratégica dos resultados  
