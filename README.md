# Desafio de Projeto: Relatórios Dinâmicos com Parâmetros no Power BI 📊
### Formação Power BI Analyst - Digital Innovation One (Módulo 6)

Este repositório contém o projeto prático desenvolvido para o módulo de criação de relatórios dinâmicos. O objetivo principal foi evoluir um relatório financeiro pré-existente, integrando **Parâmetros de Campo (Field Parameters)** para permitir uma análise flexível e interativa por parte do usuário final.

## 📑 Visão Geral do Projeto

O projeto utiliza uma base de dados financeira para explorar o desempenho de vendas e lucratividade. A grande inovação desta etapa foi a implementação de uma página exclusiva de **Análise Dinâmica**, onde o usuário não está limitado a uma visão estática, podendo alternar tanto as dimensões (categorias) quanto as métricas (valores) dos visuais em tempo real.

### 🛠️ Tecnologias Utilizadas
* **Power BI Desktop**: Modelagem de dados, DAX e visualização.
* **Parâmetros de Campo**: Funcionalidade para alternância dinâmica de eixos e medidas.

## 🚀 Implementações Realizadas

Conforme as diretrizes do desafio, o relatório foi estruturado em cinco páginas principais, com foco total no *storytelling* e na experiência do cliente:

1.  **Home Page**: Capa de apresentação com navegação intuitiva.
2.  **Principal**: Visão macro dos KPIs de vendas, segmentação por país e produto.
3.  **Detalhes**: Análise temporal por semestre e meses, incluindo histogramas de unidades vendidas.
4.  **Análise**: Correlação entre unidades e vendas, além do ranking (Top 3) de performance por país e produto.
5.  **Dinâmico (Foco do Desafio)**: Página criada para permitir a exploração multidimensional.

### 🔄 Funcionalidades da Página Dinâmica
Nesta página, foram criados visuais que respondem a dois tipos de seletores de parâmetros, permitindo que o cliente personalize sua própria visão:

* **Parâmetro de Categorias (Dimensões)**: Permite alternar o eixo dos gráficos entre:
    * `Country` (País)
    * `Segment` (Segmento)
    * `Product` (Produto)
    * `Month Name` (Mês)
* **Parâmetro de Valores (Métricas)**: Permite ao usuário escolher qual KPI deseja analisar no gráfico principal:
    * `Sales` (Vendas)
    * `Profit` (Lucro)
    * `Units Sold` (Unidades Vendidas)
    * `Gross Sales` (Vendas Brutas)

## 📖 Storytelling e Análise de Dados

A página **"Análise Dinâmica de Performance"** foi projetada para ser uma ferramenta de suporte à decisão. Em vez de múltiplos gráficos estáticos que poluem a tela, um único visual robusto permite identificar:
* Padrões de lucratividade em mercados estratégicos.
* Tendências sazonais de vendas brutas comparadas a anos anteriores.
* Comparativo direto de unidades vendidas por segmento de mercado em poucos cliques.

A interface facilita a identificação de *insights* ao consolidar a evolução mensal e o desempenho consolidado por Semestres em uma estrutura limpa e profissional, mantendo a identidade visual de todo o relatório.

---

## 🔗 Referências e Créditos
Este projeto faz parte do portfólio pessoal em desenvolvimento durante a **Formação Power BI Analyst** da [DIO](https://www.dio.me/).

---
