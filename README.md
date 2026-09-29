# Projeto Beautiful Soup — Coletores de Dados Web

Projeto em Python para coleta e extração de dados de páginas web, utilizando Requests e Beautiful Soup.

## Funcionalidades

* **Livros:** coleta títulos, preços e disponibilidade de livros do site Books to Scrape.
* **GitHub Trending:** coleta informações de repositórios em alta no GitHub, como nome, descrição, linguagem, estrelas e link.
* **Exportação CSV:** salva os dados coletados em arquivos CSV.

## Tecnologias utilizadas

* Python
* Requests
* Beautiful Soup
* CSV

## Instalação

Clone o repositório e entre na pasta do projeto.

Crie e ative um ambiente virtual:

```bash
python -m venv .venv
```

No Windows (PowerShell):

```powershell
.\.venv\Scripts\Activate.ps1
```

Instale as dependências:

```bash
python -m pip install -r requirements.txt
```

## Como executar

Coletar livros:

```bash
python main.py livros
```

Coletar repositórios do GitHub Trending:

```bash
python main.py github
```

Escolher uma linguagem e um período:

```bash
python main.py github -l javascript -p weekly
```

Executar os dois coletores:

```bash
python main.py tudo
```

## Arquivos gerados

* `livros.csv` — dados dos livros coletados.
* `repositorios_trending.csv` — dados dos repositórios do GitHub.

## Objetivo

Praticar web scraping com Python, utilizando requisições HTTP, análise de HTML e exportação de dados para arquivos CSV.
