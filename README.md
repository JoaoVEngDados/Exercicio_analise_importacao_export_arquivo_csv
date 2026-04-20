# Análise de Dados de Recursos Humanos com Pandas 📊

Este projeto consiste em um script Python para **Análise Exploratória de Dados (EDA)** aplicado a um cenário de Recursos Humanos. O objetivo é processar um banco de dados de funcionários para extrair métricas de desempenho, médias salariais e insights geográficos.

## 🚀 Funcionalidades

O script realiza um pipeline completo de manipulação de dados, incluindo:

1.  **Exploração Inicial:** Inspeção de tipos de dados, integridade de registros e visualização das primeiras linhas do dataset.
2.  **Métricas Estatísticas:** * Cálculo da média salarial geral.
    * Média salarial segmentada por profissão.
    * Identificação das cidades com maior volume de colaboradores.
3.  **Filtros Inteligentes:**
    * Identificação de colaboradores com salários acima de R$ 5.000,00.
    * Segmentação de profissionais seniores (mais de 10 anos de experiência).
4.  **Ordenação e Rankeamento:**
    * Ordenação multinível (por nome e salário).
    * Ranking de experiência profissional.
5.  **Agrupamentos Avançados (Business Intelligence):**
    * Análise de remuneração máxima, mínima e média cruzando Cidade vs. Profissão.
6.  **Exportação de Resultados:** Geração de um relatório final formatado em arquivo Excel (`.xlsx`).

## 🛠️ Tecnologias Utilizadas

* **Python 3.x**
* **Pandas:** Biblioteca principal para manipulação e análise de dados.
* **Openpyxl:** Engine para suporte e exportação de arquivos Excel.

## 📋 Estrutura do Dataset Analisado

O projeto processa colunas como:
* `id`, `nome`, `idade`
* `cidade`, `profissao`
* `salario`, `anos_experiencia`
* `data_contratacao`, `avaliacao` (Score de desempenho)

## 📖 Como Executar

1. Certifique-se de ter o Python instalado.
2. Instale as dependências necessárias:
   ```bash
   pip install pandas openpyxl
