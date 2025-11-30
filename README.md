# 📦 Análise de Inventário e Obsolescência - Los Alamos Comercial Ltda

Este repositório contém o projeto de extensão desenvolvido para a disciplina de **Tópicos de Big Data em Python**. O objetivo principal foi analisar a base de dados de insumos da empresa parceira para identificar gargalos de estoque, produtos inativos e padrões que levam à obsolescência.

## 🎯 Objetivos do Projeto
* **Mapeamento de Inatividade:** Identificar o volume de capital parado e as categorias mais críticas.
* **Saúde do Estoque:** Comparar a proporção de itens Ativos vs. Inativos (Health Check).
* **Investigação de Causas:** Analisar se fatores como "Uso Fiscal" ou a qualidade do cadastro (tamanho da descrição) influenciam no status do produto.
* **Modelagem Preditiva:** Aplicação de Regressão Linear para estimar a probabilidade de atividade de um item.

## 🛠️ Tecnologias Utilizadas
O projeto foi desenvolvido em **Python** utilizando as seguintes bibliotecas:
* **Pandas & Numpy:** Manipulação e limpeza de dados.
* **Matplotlib & Seaborn:** Visualização de dados (Gráficos de barras, pizza, boxplots, heatmaps).
* **Statsmodels:** Análise estatística avançada (OLS Regression).

## 📊 Principais Insights
Com base na análise exploratória e estatística, descobrimos que:
1.  **Foco do Problema:** A categoria `/ PECAS MECANICAS` é a líder absoluta em itens inativos.
2.  **Proporção Global:** Cerca de **38,3%** de todo o inventário analisado consta como INATIVO.
3.  **Padrão de Cadastro:** A análise bivariada e a matriz de correlação indicaram uma tendência de que produtos com descrições muito longas têm maior probabilidade de serem inativos.
4.  **Independência Fiscal:** Não foi encontrada correlação estatística relevante entre a classificação fiscal do item e seu status de atividade.

## 👨‍💻 Equipe
* Marcus Vinicius
* Gabriel Novais
* Matheus Alves

**Professor Orientador:** Fabio Da Roza Oliveira

---
*Projeto apresentado em: Dezembro/2025*
