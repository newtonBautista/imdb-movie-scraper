# imdb-movie-scraper

Este projeto realiza web scraping no site IMDb para coletar informações sobre os filmes mais populares do momento. Ele extrai dados como título, ano de lançamento, nota (rating) e sinopse e os salva em um arquivo CSV.


🚀 Funcionalidades

    Coleta os filmes em alta no IMDb
    Extrai detalhes de cada filme: título, ano de lançamento, nota e sinopse
    Usa múltiplas threads para acelerar a coleta dos dados
    Ordena os filmes pela nota (rating) de forma decrescente
    Salva os dados no arquivo movies.csv


🛠️ Tecnologias

    Python 3
    Requests → Para fazer as requisições HTTP
    BeautifulSoup → Para análise e extração do HTML
    CSV → Para salvar os resultados em um arquivo
    ThreadPoolExecutor → Para execução de múltiplas threads e maior eficiência


📋 Como usar

1. Clone este repositório:

```bash
git clone https://github.com/newtonBautista/imdb-movie-scraper.git

2. (Opcional, mas recomendado) Instale os pré-requisitos no Linux:

sudo apt update
sudo apt install python3 python3-pip python3-venv

3. Crie e ative um ambiente virtual:

🐧 Linux/macOS:

python3 -m venv venv
source venv/bin/activate

🪟 Windows (CMD):

python -m venv venv
venv\Scripts\activate

🪟 Windows (PowerShell):

python -m venv venv
venv\Scripts\Activate.ps1

4. Instale as dependências:

pip install -r requirements.txt

5. Execute o script:

python scraper.py

6. Resultado:

Os dados coletados serão salvos no arquivo movies.csv no mesmo diretório.


---
   

⚙️ Licença

Este projeto está licenciado sob a MIT License - veja o arquivo LICENSE para mais detalhes.


📞 Contato

    Isaac
    Email: isaacnewton48@hotmail.com

