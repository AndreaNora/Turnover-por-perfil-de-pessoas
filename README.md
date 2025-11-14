# 📊 Análise de Rotatividade por Perfil de Pessoas (Power BI)

## Status do Projeto
> ✅ **CONCLUÍDO:** Dashboard finalizado e documentação publicada.

---

## 🎯 Objetivo e Contexto
Este projeto visa analisar o perfil de funcionários que impacta a alta rotatividade (turnover) em uma empresa. O foco é identificar padrões, para reduzir o turnover e fornecer **insights acionáveis** para a contratação mais assertiva, reduzindo os custos de admissões e  rescisões, ao mesmo tempo em que torna a produtividade maior com funcionários estáveis.

## 🛠️ Tecnologias e Ferramentas
- **Ferramenta de BI:** Power BI
- **Linguagem:** DAX (Data Analysis Expressions) e Power Query (M)
- **Visualização:** Dashboards

---

## 🖼️ Dashboard e Resultados
> 📊 Visão geral da análise de rotatividade dos funcionários:
![Dashboard](https://raw.githubusercontent.com/AndreaNora/Turnover-por-perfil-de-pessoas/main/An%C3%A1lise_rotatividade_funcion%C3%A1rios.png)

> 📊 Análise das saídas:
![Dashboard](https://raw.githubusercontent.com/AndreaNora/Turnover-por-perfil-de-pessoas/main/An%C3%A1lise_rotatividade_funcion%C3%A1rios2.png)




## 📈 Metodologia e Análise

1. **Coleta de Dados**: Os dados foram extraídos da internet, sendo uma base de dados **fictícia** de Recursos Humanos, utilizada para fins de estudo e análise. 
2. **Tratamento no Power Query** : Em colunas de texto, os valores em branco foram preenchidos com "N/A" para garantir a integridade da análise.
3. **Cálculos DAX Chave** : Cálculo da Idade Média e Mediana - Foi calculada a média da idade dos funcionários (usando AVERAGE) e, para lidar com possíveis outliers que poderiam distorcer a média, foi também implementada a mediana (usando MEDIAN) como uma medida mais robusta da centralidade da idade. Cálculo do Tempo de Casa - Utilizou-se a função DATEDIFF para determinar o tempo de serviço de cada funcionário, calculando a diferença em dias/meses/anos entre a data de admissão e a data de demissão e a data atual, para funcionários ativos.

## 💡**Principais Insights** :

O gênero feminino são os que mais saíram, representado por 36,9% do total de pessoas que responderam. 	

A idade média das pessoas que saíram da empresa é de 40,77 anos, o que significa que a empresa pode estar perdendo profissionais já consolidados em suas carreiras. 

O departamento com maior rotatividade é o RH, seguido por Operações e Marketing. 
O Financeiro e TI são os que menos contribuem para o volume total de rotatividade.

Pessoas casadas são o grupo com maior volume de saídas, seguidos de perto por Solteiros e Divorciados. A diferença é pequena, mas reforça a perda de profissionais com mais responsabilidades familiares/pessoais.

Pessoas sedentárias foram as que mais saíram. 

RH perdeu mais funcionários pela mudança de cidade, já a Operações perdeu funcionários por conta de salário. Funcionários de Marketing deixa a empresa por novas oportunidades. 
TI e Financeiro tem perdido funcionários por conta de salários e novas oportunidades. 

Observa-se que há uma tendência de queda acentuada e consistente (em forma de "U" invertido), o que significa que, nos últimos anos, a capacidade de retenção da empresa está piorando rapidamente.


## 🎯 **Plano de Ação** :

• Reduzir saídas do gênero feminino

> Implantar mais flexibilidade, apoio familiar, revisão de equidade salarial, jornada híbrida, auxílio-creche, banco de horas.

• Reter profissionais experientes (40+ anos)

> Criar trilhas de carreira sênior, mentoria e benefícios focados em bem-estar.

• Atuar nos departamentos críticos (RH, Operações, Marketing):
  
  > • RH: ampliar trabalho remoto para reduzir saídas por mudança de cidade.
 
  > •	Operações: revisar salários e criar incentivos.
 
  > •	Marketing: acelerar plano de carreira e treinamentos.

• Melhorar retenção em TI e Financeiro

> Alinhar salários ao mercado, benchmark salarial anual com empresas do mesmo setor, estabelecer trilha de crescimento transparente e criar programas de inovação para manter profissionais engajados.

• Apoiar profissionais casados

> Ajustar políticas de flexibilidade e oferecer benefícios focados em bem-estar familiar planos de saúde mais amplos, horários flexíveis, home office.

• Melhorar saúde e engajamento de colaboradores sedentários

> Implementar programas de bem-estar e saúde corporativa, como academia conveniada, desafios internos de saúde, ginástica laboral. Campanhas de saúde mental e acompanhamento médico preventivo.

• Atuar nos motivos de saída por setor

> Criar entrevistas de desligamento estruturadas e ações direcionadas com dashboards internos para monitoramento mensal dos motivos de saída e plano de ação individual por liderança.

• Reverter a tendência geral de aumento da rotatividade

> Criar um Comitê de Retenção com RH + líderes-chave e criar e revisar indicadores trimestralmente para aplicar People Analytics continuo. Padronizar avaliações de clima organizacional e engajamento. Identificar picos de saída ao longo do ano e atuar preventivamente.
