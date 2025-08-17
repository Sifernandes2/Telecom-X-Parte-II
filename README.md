# 📊 Telecom X – Parte II: Previsão de Churn de Clientes

## 🎯 Objetivo do Projeto

Este projeto tem como foco prever o **churn de clientes** (cancelamento voluntário) em uma empresa de telecomunicações. 

## 🎯 Propósito da Análise

A análise visa identificar os principais fatores que influenciam a evasão e propor estratégias de retenção com base em insights extraídos.

---

## 📁 Estrutura do Projeto

A análise foi conduzida em ambiente interativo (Google Colab), utilizando bibliotecas como:

- `pandas` para manipulação de dados
- `seaborn` e `matplotlib` para visualizações
- `scikit-learn` para modelagem preditiva

### 🔍 Etapas Realizadas

1. **Preparação dos dados**
   - Extração do Arquivo Tratado
   - Remoção de colunas irrelevantes
  
2. **Separação de variáveis**
   - Explicativas
   - Alvo

3. **Transformação**
   - `OneHotEncoding` para variáveis categóricas
   - Proporção de Evasão
   - Analise Correlação
  
4. **Separação dos dados**
   - 70% treino / 30% teste
   - Balanceamento de Classes
   - Normalização

5. **Modelagem**
   - Teste com `Dummy`, Árvore de Decisão`, `KNN`
   - Avaliação com métricas: `accuracy`, `recall`, `f1-score`, `ROC-AUC`

---

## 📈 Principais Insights

- Clientes com **contrato mensal** apresentam maior taxa de churn.
- **Pagamentos via Mailed check e Electronic check** estão mais associados à evasão.
- **Clientes com Fiber optic** apresentam maior taxa de evasão.
- Perfis com **baixo tempo de fidelidade** e **alto custo mensal** são mais vulneráveis à saída.

---

## ▶️ Como Executar o Notebook
Acesse o Google Colab ou ambiente local.

Faça upload do arquivo Challenge_TelecomX_Parte2.ipynb.

## 💡 Recomendação Final
Incentivar Contratos de Longo Prazo.

Melhorar a Experiência com Pagamentos.

Monitorar Clientes com Fiber Optic.


