# Projeto esgData

## O que é?

O projeto esgData é um programa que utiliza a API do Yahoo Finance para coletar dados ESG das empresas listadas no S&P500. Os dados ESG são fornecidos pela Sustainlytics. Para obter mais informações sobre os dados, consulte a documentação da API do Yahoo Finance.

## Como usar?

Para utilizar o projeto esgData, siga as etapas abaixo:

1. Faça o download do Jupiter Notebook do repositório.
2. Baixe o arquivo `sp_500_stocks.csv`.
3. Abra o Jupiter Notebook e altere os parâmetros conforme necessário para coletar e visualizar os dados desejados.

## Como funciona?

O programa funciona realizando requisições na API do Yahoo Finance utilizando o endpoint "https://query2.finance.yahoo.com/v1/finance/esgChart?symbol=". Essas requisições retornam valores históricos de dados ESG das empresas listadas no S&P500.

## Quais parâmetros posso alterar?

Você pode personalizar diversos aspectos do projeto esgData:

1. **Selecionando empresas:** Altere os tickers no arquivo `sp_500_stocks.txt` para selecionar apenas as empresas que você deseja visualizar.

2. **Definindo um intervalo temporal:** Na seção "Selecionando empresas com melhores índices ESG", você pode configurar um filtro de intervalo temporal para os dados desejados.

3. **Visualizando as piores empresas ESG:** Na mesma seção mencionada acima, você pode alterar o método `.head()` para `.tail()` para visualizar as piores empresas em termos de índices ESG.

Aproveite o projeto esgData e explore os dados ESG das empresas no S&P500!
