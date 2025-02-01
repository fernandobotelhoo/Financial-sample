# Financial-sample

# 📊 Desafio de Modelagem Dimensional - Star Schema

## 🎯 Objetivo

## Este projeto tem como objetivo criar um modelo de dados dimensional no formato Star Schema a partir da tabela Financial Sample. O foco é organizar os dados em tabelas fato e dimensão para facilitar a análise e visualização no Power BI.


## 🏗️ Estrutura do Modelo

## A partir da tabela única Financial Sample, foram criadas as seguintes tabelas:

### 🔹 Tabelas Dimensão

- D_Produtos (Informações sobre os produtos)

- D_Produtos_Detalhes (Detalhamento dos produtos)

- D_Descontos (Informações sobre descontos)

- D_Calendário (Criada com DAX CALENDAR())

- D_Detalhes (Detalhes adicionais sobre vendas)

🔹 Tabela Fato

- F_Vendas (Consolidação das informações de vendas)

## 🛠️ Etapas do Processo

- Criação das Tabelas Dimensão a partir da tabela original Financial Sample.

- Definição da Tabela Fato consolidando os principais dados para análise.

- Criação da Tabela D_Calendário com DAX usando CALENDAR().

- Reorganização das colunas e limpeza dos dados.

- Criação de medidas DAX para análise, como cálculos de média, mediana e totais.

- Relacionamento entre as tabelas no Power BI.
