![Banner do Projeto](Banner.png)

# P8_Megaline – Classificação de Plano Celular

Este projeto desenvolve modelos de machine learning para prever o plano ideal (Smart ou Ultra) para clientes da operadora Megaline, com base em seu comportamento mensal de uso.

## 📂 Dados
- `users_behavior.csv` — Comportamento mensal (chamadas, mensagens, internet).
- `is_ultra` — Plano atual (0 = Smart, 1 = Ultra).

## 📊 Modelos Utilizados
- Regressão Logística
- Árvore de Decisão
- Floresta Aleatória (melhor desempenho)

## 🏁 Resultados
- Melhor modelo: **Floresta Aleatória**
- Acurácia no conjunto de teste: **~0.80**

## 📁 Arquivo principal
- `P8_Megaline.ipynb`