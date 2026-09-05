# 📊 Análise de Risco e Retorno — ITUB4 vs IBOV vs SELIC

## 📌 Descrição

Este projeto realiza uma análise quantitativa da ação ITUB4, comparando seu desempenho com o índice IBOV e com a taxa livre de risco (SELIC).

O foco está na avaliação de retorno, risco e eficiência, utilizando métricas amplamente utilizadas no mercado financeiro.

## 🎯 Objetivos
    - Comparar o desempenho da ITUB4 com o IBOV
    - Avaliar o nível de risco do ativo
    - Medir a eficiência do retorno (Sharpe Ratio)
    - Analisar perdas históricas (Drawdown)
    - Comparar com a taxa livre de risco (SELIC)

## 📊 Métricas Utilizadas
    - 📈 Retorno Acumulado
    - 📉 Volatilidade Anualizada
    - ⚖️ Sharpe Ratio
    - ⚠️ Value at Risk (VaR 95%)
    - 📉 Drawdown Máximo
   
## 🧠 Metodologia

 - Cálculo de retornos diários a partir dos preços de fechamento
 - Volatilidade anualizada utilizando √252 (dias úteis)
 - Sharpe Ratio ajustado pela SELIC diária
 - VaR estimado via quantil histórico (5%)
 - Drawdown calculado com base no pico histórico acumulado

## 📈 Resultados
   Métrica	                                ITUB4
 - Retorno Acumulado (2021–2025)	        97.7%
 - Volatilidade Anual	                    23.77%
 - Sharpe Ratio	                            0.26
 - VaR Diário (95%)	                        -2.29%
 - Drawdown Máximo	                        -35.87%

## 🔍 Principais Insights
 - A ITUB4 apresentou retorno superior ao IBOV, indicando geração de valor acima do mercado
 - O ativo possui alta volatilidade, caracterizando maior exposição ao risco
 - O Sharpe Ratio baixo (0.26) indica baixa eficiência risco-retorno
 - O drawdown de -35.87% evidencia perdas relevantes em períodos de estresse
 - A comparação com a SELIC mostra a importância do custo de oportunidade

## 📊 Visualizações

O projeto inclui gráficos de:
 - Preço e volume
 - Médias móveis (MM20, MM50, MM200)
 - Retorno acumulado (base 100)
 - Drawdown
📁 Os gráficos estão disponíveis na pasta /imagens

## 🛠️ Tecnologias Utilizadas
Python
Pandas
NumPy
Matplotlib
yFinance

## 📂 Estrutura do Projeto
analise-itub4/
│
├── imagens/             # gráficos gerados
├── notebook.ipynb       # análise exploratória
├── analise.py           # versão estruturada do código
└── README.md

## 📌 Conclusão

A ação ITUB4 apresentou desempenho superior ao benchmark em termos de retorno, porém com maior exposição ao risco e menor eficiência risco-retorno.

Os resultados reforçam que decisões de investimento devem considerar não apenas o retorno absoluto, mas também o risco assumido para obtê-lo.