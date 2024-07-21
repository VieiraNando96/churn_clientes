# Análise de Cancelamentos de Clientes

## Objetivo: 

Este projeto visa analisar os dados de cancelamento de clientes para identificar padrões e propor ações que possam reduzir a taxa de cancelamento.

## Descrição:

O notebook analise.ipynb realiza uma série de passos para entender e tratar os dados de cancelamento:

1 - **Importação de Bibliotecas:** pandas e matplotlib.pyplot

2 - **Carregamento dos Dados:** A base de dados cancelamentos.csv é carregada e visualizada.

3 - **Limpeza dos Dados:**
  - Verificação de valores nulos e remoção dos mesmos.
  - Remoção da coluna CustomerID, que não é relevante para a análise.

4 - **Análise dos Cancelamentos:**
  - Contagem e porcentagem de cancelamentos.
  - Geração de gráficos para entender os cancelamentos com base em diferentes variáveis.

5 - **Ajustes Baseados na Análise:**
  - Remoção de clientes com plano mensal, alta quantidade de ligações para o call center, muitos dias de atraso no pagamento e idade acima de 50 anos.

6 - **Propostas de Ação:**
  - Migração de clientes do plano mensal para outros planos.
  - Criação de alertas para tratamento diferenciado para clientes com até 3 ligações no call center.
  - Contato com clientes com pagamentos atrasados em 5 dias para negociação.
  - Foco em campanhas de marketing para pessoas com menos de 50 anos.

## **Resultados:**
  Com as ações propostas, a taxa de cancelamento pode ser reduzida de 56.7% até 12.2%.

## **Como Utilizar:**

1- Clone o repositório:

    git clone https://github.com/VieiraNando96/churn_clientes.git

2 - Navegue até o diretório do projeto:

    cd seu-repositorio
    
3 - Instale as dependências necessárias:

    pip install pandas matplotlib

4 - Execute o notebook analise.ipynb em um ambiente Jupyter Notebook ou Jupyter Lab.

