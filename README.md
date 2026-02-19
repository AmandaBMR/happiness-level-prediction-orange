# happiness-level-prediction-orange
# Previsão do Nível de Felicidade (Supervisionado) — 2020–2023

## Objetivo
Classificar países em Baixa/Média/Alta felicidade a partir de indicadores socioeconómicos.

## Stack
Orange Data Mining · Validação cruzada estratificada (10 folds)

## Dataset
548 registos país-ano (2020–2023), sem valores em falta.

## Modelos testados
Decision Tree · kNN · Logistic Regression · Random Forest

## Avaliação
Accuracy · Precision · Recall · F1 (macro) · Matriz de confusão

## Reprodutibilidade
- Export do workflow do Orange (ficheiro)
- Configuração de discretização (k=3, equal frequency)
