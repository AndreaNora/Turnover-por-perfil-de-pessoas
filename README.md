# 📊 Análise de Rotatividade por Perfil de Pessoas (Power BI)

## Status do Projeto
> 🚧 **EM ANDAMENTO (Documentação):** Este projeto está sendo documentado. O dashboard Power BI e as análises já estão finalizadas, e o Estudo de Caso (Metodologia e Resultados) será adicionado em breve.

---

## 🎯 Objetivo e Contexto
Este projeto visa analisar o perfil de funcionários que impacta a alta rotatividade (turnover) em uma empresa. O foco é identificar padrões, para reduzir o turnover e fornecer **insights acionáveis** para a contratação mais assertiva, reduzindo os custos de admissões e  rescisões, ao mesmo tempo em que torna a produtividade maior com funcionários estáveis.

## 🛠️ Tecnologias e Ferramentas
- **Ferramenta de BI:** Power BI
- **Linguagem:** DAX (Data Analysis Expressions) e Power Query (M)
- **Visualização:** Dashboards

---

## 🖼️ Dashboard e Resultados (A ser preenchido)


## 📈 Metodologia e Análise (A ser preenchido)

1. **Coleta de Dados**: Os dados foram extraídos da internet, sendo uma base de dados **fictícia** de Recursos Humanos, utilizada para fins de estudo e análise. 
2. **Tratamento no Power Query** : Em colunas de texto, os valores em branco foram preenchidos com "N/A" para garantir a integridade da análise.
3. **Cálculos DAX Chave** : Cálculo da Idade Média e Mediana - Foi calculada a média da idade dos funcionários (usando AVERAGE) e, para lidar com possíveis outliers que poderiam distorcer a média, foi também implementada a mediana (usando MEDIAN) como uma medida mais robusta da centralidade da idade. Cálculo do Tempo de Casa - Utilizou-se a função DATEDIFF para determinar o tempo de serviço de cada funcionário, calculando a diferença em dias/meses/anos entre a data de admissão e a data de demissão e a data atual, para funcionários ativos.
4. **Principais Insights** :
