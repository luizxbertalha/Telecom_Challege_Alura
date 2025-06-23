# Telecom_Challege_Alura

# Análise de Evasão de Clientes (Churn) - Telecom X

## 1. Objetivo do Projeto

Este projeto realiza uma análise exploratória completa sobre um conjunto de dados de uma empresa de telecomunicações (Telecom X). O objetivo principal é identificar os principais fatores que influenciam a evasão de clientes (churn), compreendendo os perfis, comportamentos e características dos clientes que cancelam o serviço.

A partir dos insights gerados, o projeto busca fornecer recomendações estratégicas e baseadas em dados para ajudar a empresa a reduzir sua taxa de churn, aumentar a retenção e fortalecer a lealdade de seus clientes.

## 2. Fonte de Dados

O dataset utilizado foi extraído via API do repositório [challenge2-data-science](https://github.com/ingridcristh/challenge2-data-science/blob/main/TelecomX_Data.json) no GitHub.

Os dados estão em formato JSON e apresentam uma **estrutura aninhada**, com informações de clientes, contas e serviços agrupadas em diferentes objetos. Um passo crucial do projeto foi o tratamento dessa estrutura para "achatar" os dados em um formato tabular adequado para a análise.

## 3. Tecnologias Utilizadas

* **Python 3.x**
* **Pandas:** Para manipulação e análise dos dados.
* **NumPy:** Para operações numéricas.
* **Matplotlib & Seaborn:** Para visualização de dados e criação de gráficos.
* **Requests:** Para realizar a extração dos dados diretamente da URL da API.

## 4. Estrutura do Projeto

O projeto é composto por um script principal que automatiza todo o processo de análise:

## 5. Como Executar o Projeto

Para replicar esta análise, siga os passos abaixo:

**a. Pré-requisitos:**
* Ter o Python 3 instalado em seu sistema.

**b. Clonar ou Baixar o Projeto:**
* Faça o download do script `TelecomX_BR_Challenge.ipynb` e salve-o em uma pasta de sua preferência.

**c. (Opcional, mas recomendado) Criar um Ambiente Virtual:**
```bash
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate
