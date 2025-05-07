# Análise de Crédito com Machine Learning

Este projeto tem como objetivo prever o **score de crédito** de novos clientes com base em dados históricos utilizando algoritmos de Machine Learning.

## 🔧 Tecnologias e Bibliotecas Utilizadas
- Python
- Pandas
- Scikit-learn
- LabelEncoder
- RandomForestClassifier
- KNeighborsClassifier

## 📊 Etapas do Projeto
1. **Importação dos dados**: Leitura dos dados de clientes (`clientes.csv`) e novos clientes (`novos_clientes.csv`);
2. **Pré-processamento**: Transformação de variáveis categóricas com `LabelEncoder`;
3. **Separação entre treino e teste** com `train_test_split`;
4. **Criação e treino dos modelos**:
   - Random Forest
   - K-Nearest Neighbors
5. **Avaliação da acurácia dos modelos**;
6. **Previsão do score de novos clientes**.

## 🎯 Resultado
- O modelo com melhor desempenho foi utilizado para prever os scores de crédito de novos clientes;
- Acurácia das previsões avaliada com `accuracy_score`.

## 📁 Arquivos
- `clientes.csv`: Dados históricos de clientes;
- `novos_clientes.csv`: Base para novas previsões;
- `codigo.py`: Código completo do projeto.

## 📌 Objetivo
Projeto voltado para prática de Machine Learning supervisionado na área financeira.
