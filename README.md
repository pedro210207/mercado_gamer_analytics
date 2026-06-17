<div align="center">

# 🎮 Mercado Gamer Analytics
### Data Engineering & Business Intelligence (BI) Project

![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow?style=for-the-badge)

---
</div>

## 📝 Sobre o Projeto
<div align="justify">
Este projeto consiste no desenvolvimento de uma plataforma analítica <strong>End-to-End</strong> criada para mapear tendências, analisar a lucratividade e identificar a dominância de diferentes publishers e estúdios no mercado global de games. O objetivo principal é transformar dados brutos extraídos diretamente da web em insights estratégicos para tomadas de decisão.
</div>

---

## 🏗️ Arquitetura da Solução (Pipeline de Dados)
<div align="justify">
O projeto está estruturado seguindo as melhores práticas de engenharia e análise de dados do mercado:
<ol>
  <li><strong>Ingestão & ETL (Python):</strong> Consumo de dados reais através de APIs públicas utilizando a biblioteca <code>Requests</code>, seguido pelo tratamento, limpeza e modelagem dos dados com <code>Pandas</code>.</li>
  <li><strong>Data Warehouse / Data Lake (MySQL):</strong> Armazenamento e persistência dos dados tratados em um banco de dados relacional local, estruturado no modelo multidimensional <strong>Star Schema</strong> (Tabelas Fato e Dimensão) e otimizado via Views.</li>
  <li><strong>Data Visualization (Power BI):</strong> Criação de um dashboard executivo interativo com aplicação de Storytelling e cálculos avançados em <code>DAX</code> para responder a perguntas de negócio.</li>
</ol>
</div>

---

## 📁 Estrutura do Repositório
```text
├── data/          # Arquivos de dados brutos e tratados (CSVs/JSONs)
├── notebooks/     # Scripts Python e Jupyter Notebooks de ETL
├── sql/           # Scripts MySQL (Criação de tabelas, Views e queries)
├── dashboard/     # Arquivo .pbix do Power BI e capturas de tela do painel
└── README.md      # Documentação do projeto
