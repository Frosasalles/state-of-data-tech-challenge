# 📘 Escopo do Projeto — Tech Challenge  
### Pós Tech FIAP — Engenharia de Dados  
### State of Data Brazil (2023, 2024, 2025/26)

---

## 📌 1. Resumo do Tech Challenge

Este projeto tem como objetivo construir um **Data Lake completo na AWS**, utilizando os datasets da pesquisa **State of Data Brazil**, realizada pela comunidade Data Hackers em parceria com a Bain & Company.

O desafio envolve:

- ingestão de dados brutos no Amazon S3  
- catalogação automática com AWS Glue Crawler  
- processamento e transformação com Glue Jobs (PySpark)  
- criação das camadas Bronze, Silver e Gold  
- consultas analíticas via Amazon Athena  
- construção de dashboards e storytelling  
- entrega de insights sobre o mercado brasileiro de dados  

O projeto simula o fluxo real de um time de Engenharia de Dados em uma empresa moderna.

---

## 🎯 2. Objetivos do Projeto

### **Objetivo Geral**
Construir um pipeline de dados robusto, escalável e bem documentado, seguindo boas práticas de arquitetura de Data Lake.

### **Objetivos Específicos**
- Criar um repositório organizado e versionado no GitHub  
- Estruturar o Data Lake com camadas Bronze, Silver e Gold  
- Processar os datasets utilizando PySpark no AWS Glue  
- Criar tabelas analíticas para consumo em Athena  
- Desenvolver dashboards com insights relevantes  
- Documentar arquitetura, decisões técnicas e resultados  
- Apresentar conclusões executivas sobre o mercado de dados  

---

## 📦 3. Datasets Utilizados

### **State of Data Brazil 2023**
- 5.293 respondentes  
- Dados demográficos, carreira, salários, tecnologias, IA generativa  
- Perguntas multi-valoradas com colunas no formato `P3a_1`, `P8_a_2`, etc.  
- Dados anonimizados pela Data Hackers  

### **State of Data Brazil 2024**
- 5.217 respondentes  
- Estrutura semelhante ao dataset de 2023  
- Evolução de tendências e adoção de IA  

### **State of Data Brazil 2025–2026**
- 3.495 respondentes  
- Continuidade da série histórica  
- Foco em maturidade de dados e IA nas empresas  

---

## 🏗️ 4. Arquitetura da Solução

A arquitetura segue o padrão moderno de Data Lake:


