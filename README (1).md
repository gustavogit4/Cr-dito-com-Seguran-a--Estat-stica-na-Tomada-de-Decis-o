
# Modelo Estatístico para Risco de Crédito com Regressão Logística

Este projeto tem como objetivo construir um modelo estatístico para prever o risco de crédito de clientes com base em dados socioeconômicos e financeiros. A abordagem utilizada foi a regressão logística, respeitando todas as etapas clássicas da análise estatística.

## Objetivo

Prever se um cliente é um bom ou mau pagador, classificando-o como:

- **1**: Bom risco de crédito
- **0**: Mau risco de crédito

## Etapas do Projeto

1. Importação e exploração dos dados
2. Análise exploratória da variável-alvo
3. Análise das variáveis explicativas
4. Codificação de variáveis categóricas
5. Separação entre variáveis independentes (X) e alvo (y)
6. Ajuste do modelo estatístico (regressão logística)
7. Avaliação de desempenho (acurácia, recall, AUC)
8. Verificação das premissas estatísticas
9. Interpretação dos resultados
10. Conclusão e recomendações

## Principais Resultados

- **Acurácia:** 0.79
- **Recall (bons pagadores):** 0.90
- **Recall (maus pagadores):** 0.53
- **AUC (curva ROC):** 0.83

O modelo demonstrou bom desempenho em prever clientes adimplentes, com razoável capacidade de identificar inadimplentes.

## Limitações

- Desequilíbrio entre classes no dataset
- Baixa performance na identificação de maus pagadores
- Conjunto de dados limitado a informações cadastrais
- Base original de contexto europeu
- Ausência de dados comportamentais e históricos de inadimplência

## Tecnologias Utilizadas

- Python 3
- Pandas, NumPy
- Seaborn, Matplotlib
- Statsmodels, Scikit-learn

## Dataset

Fonte: [UCI German Credit Data](https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data))

## Autor

Gustavo De Paula  
Perfil: [@gustavogit4](https://github.com/gustavogit4)
