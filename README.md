![Banner do Projeto](Banner.png)

# 📱 Projeto 8 - P8_Megaline – Classificador de Plano Celular

Este projeto tem como objetivo prever automaticamente o plano de celular ideal (**Smart** ou **Ultra**) para clientes da operadora **Megaline**, com base no seu comportamento de uso (chamadas, mensagens e internet).

---

## 📊 Objetivo do Projeto

- Desenvolver modelos de machine learning para classificar o plano ideal de cada cliente.
- Aumentar a adesão aos novos planos da Megaline, promovendo migração assertiva.
- Superar o limite mínimo de **0.75 de acurácia**.

---

## 🗂 Estrutura do Banco de Dados

A base de dados contém registros mensais de uso individual por cliente:

### Colunas do dataset:

- `calls`: número de chamadas realizadas
- `minutes`: tempo total de chamadas (em minutos)
- `messages`: número de mensagens enviadas
- `mb_used`: volume de dados (em megabytes)
- `is_ultra`: plano atual (1 = Ultra, 0 = Smart)

---

## 🧪 Etapas do Projeto

### 📌 Etapa 1: Pré-processamento e Divisão dos Dados
- Separação em treino (60%), validação (20%) e teste (20%).
- Aplicação de `StandardScaler` para normalização das variáveis.

### 📌 Etapa 2: Treinamento e Avaliação de Modelos
Modelos testados:
- Regressão Logística
- Árvore de Decisão
- Floresta Aleatória

Otimização com `GridSearchCV` e validação cruzada.

---

## 📌 Tecnologias Utilizadas

![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white&style=flat)
![Pandas](https://img.shields.io/badge/-Pandas-150458?logo=pandas&logoColor=white&style=flat)
![scikit-learn](https://img.shields.io/badge/-Scikit--Learn-F7931E?logo=scikit-learn&logoColor=white&style=flat)
![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?logo=jupyter&logoColor=white&style=flat)

---

## 📈 Resultados e Conclusões

| Modelo               | Acurácia (Validação) | Acurácia (Teste) |
|----------------------|----------------------|------------------|
| Regressão Logística  | ~0.70                | —                |
| Árvore de Decisão    | ~0.81                | —                |
| **Floresta Aleatória**   | **~0.83**            | **~0.80**        |

- O modelo de **Floresta Aleatória** foi o melhor classificador.
- Atingiu **~80% de acurácia no conjunto de teste**, superando o mínimo exigido.
- Métricas adicionais como matriz de confusão e relatório de classificação foram utilizadas.

---

## 👩‍💻 Desenvolvido por

**Marcia Bayardino Weyne**  
📫 mbweyne@gmail.com  
[![GitHub](https://img.shields.io/badge/-GitHub-181717?logo=github&logoColor=white&style=flat)](https://github.com/mbweyne)  
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?logo=linkedin&logoColor=white&style=flat)](https://www.linkedin.com/in/marcia-bayardino-weyne)
