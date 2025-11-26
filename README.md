# WebScraping-Selenium

Este repositório contém um projeto de Web Scraping utilizando Python e Selenium para coletar informações de produtos de hardware no site Pichau.  
O foco atual é extrair dados de placas de vídeo e organizar os resultados em arquivos CSV.

## Objetivo do Projeto

- Automatizar a coleta de dados de produtos da Pichau.
- Obter informações como nome do produto, preço e disponibilidade.
- Exportar os dados em formato CSV para análise.
- Servir como estudo prático de Selenium, automação e scraping real.

## Tecnologias Utilizadas

- Python 3
- Selenium
- Pandas
- ChromeDriver (ou outro WebDriver compatível)
- Jupyter Notebook


## Pré-requisitos

- Python 3.9+
- Navegador Chrome (ou outro de sua escolha)
- WebDriver compatível instalado
- Instalar dependências:

```bash
pip install selenium pandas
```

## Funcionamento do Script
O script coleta.ipynb realiza:
- Abertura do navegador via Selenium WebDriver.
- Navegação até a página de placas de vídeo da Pichau.
- Scroll da página para carregar todos os produtos.
- Extração de nome, preço e informações disponíveis.
- Criação de um DataFrame com Pandas.
- Exportação dos dados para CSV.

