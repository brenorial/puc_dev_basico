# Projeto da PUC-RIO - Desenvolvimento Full Stack Básico

Essa branch é desenvolvida para testes. 
Lembrar de sempre fazer pull request quando finalizado, testado e aprovadas as inovações.

Este é um projeto desenvolvido como parte da disciplina **Desenvolvimento Full Stack Básico** da **PUC-RIO**. O objetivo é construir uma aplicação web utilizando **Python (Flask)** e **SQLAlchemy**, explorando conceitos fundamentais de backend, banco de dados e APIs.

## O que este projeto faz?

O projeto é uma **API para gerenciamento de produtos e comentários**, onde você pode:

- **Adicionar produtos** com nome, quantidade e valor.
- **Consultar produtos já cadastrados** no banco de dados.
- **Adicionar comentários** a um produto específico.
- **Armazenar tudo no banco de dados SQLite** de forma organizada.

## Tecnologias utilizadas

- **Python 3.12.1**
- **Flask** (para criar a API)
- **SQLAlchemy** (para gerenciar o banco de dados)
- **SQLite** (banco de dados local)
- **Git & GitHub** (para versionamento do código)

## Como rodar o projeto?

1. Clone este repositório:

   ```sh
   git clone https://github.com/brenorial/puc_dev_basico.git
   ```

2. Acesse a pasta do projeto:

   ```sh
   cd puc_dev_basico
   ```

3. Crie e ative um ambiente virtual (opcional, mas recomendado):

   ```sh
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate  # Windows
   ```

4. Instale as dependências:

   ```sh
   pip install -r requirements.txt
   ```

5. Rode a aplicação:

   ```sh
   python aula-3/meu_app_api/main.py
   ```

6. Acesse a API no navegador ou via Postman:

   ```
   http://127.0.0.1:5000/
   ```

## Próximos passos

- Melhorar a interface para acessar os produtos.
- Criar autenticação de usuários.
- Integrar com um frontend futuramente.
