# data-science-radix

## Descrição:
O conjunto de dados contém 9358 resultados médios de 5 sensores químicos de um dispositivo multisensor (PTXX.SX). O dispositivo estava localizado a nível da rua, dentro de uma cidade significativamente poluída. Os dados foram registrados de março de 2004 a fevereiro de 2005 (um ano). Valores ausentes são marcados com o valor -200. A medida de outros sensores também está disponível e algumas podem ser redundantes. A variável chave a ser analisada é PT08.S1 (CO), concentração de CO na atmosfera.

## Informação das colunas:

01. Date (DD/MM/YYYY)
02. Time (HH.MM.SS)
03. PT08.S1 (CO) – Variável de predição
04. Non Metanic HydroCarbons Concentration (mg/m^3)
05. 4 Benzene Concentration (mg/m^3)
06. PT08.S2 (NMHC)
07. NOx Concentration (ppb)
08. PT08.S3 (NOx)
09. 8 NO2 Concentration (mg/m^3)
10. PT08.S4 (NO2s)
11. PT08.S5 (O3)
12. Temperature (C)
13. Relative Humidity (%)
14. AH Absolute Humidity

## Perguntas:

1. Escolha uma estratégia de tratamento de valores faltantes e outliers e justifique sua escolha.
2. Para as quartas-feiras, quais os horários de pico na cidade (de maior concentração de CO) ?
3. Quais as variáveis mais correlacionadas com a variável de predição?
4. Crie um modelo de regressão de PT08.S1 a partir das demais variáveis. Avalie usando as métricas que julgar pertinente para o problema.
5. Pergunta bônus: como as estações do ano interferem nas variáveis/predição e qual sua proposta de solução?

Essas perguntas servem apenas para direcionar a análise. Sinta-se livre para surpreender.
