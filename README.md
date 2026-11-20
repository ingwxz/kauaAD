# API de Upload e Download de Arquivos

## Sobre o projeto

Este projeto é focado em uma API desenvolvida em Python utilizando o framework Flask, com o objetivo de permitir o envio (upload) e o download de arquivos.

O projeto foi desenvolvido como atividade avaliativa da disciplina de Desenvolvimento de Aplicações.

## Tecnologias utilizadas

- Python
- Flask
- SQLite
- Gunicorn
- Git e GitHub
- Render

## Funcionalidades

- Envio de arquivos (upload).
- Download de arquivos.
- Armazenamento de informações no banco de dados.
- Organização das rotas da API.

## Estrutura do projeto

- `app.py`: arquivo principal da aplicação.
- `controllers/`: controladores do projeto.
- `database/`: configuração do banco de dados.
- `models/`: modelos de dados.
- `routes/`: rotas da API.
- `uploads/`: armazenamento de arquivos enviados.

## Como executar o projeto localmente

### 1. Clonar o repositório

```bash
git clone https://github.com/CamilyCLY/kaua-AD.git
```

### 2. Entrar na pasta do projeto

```bash
cd kaua-AD
```

### 3. Instalar as dependências

```bash
pip install -r requirements.txt
```

### 4. Executar a aplicação

```bash
python app.py
```

### 5. Acessar a API

Abra o navegador e acesse:

```text
http://127.0.0.1:5000/
```

## Rotas da API

| Rota | Descrição |
|---|---|
| `/` | Página inicial da API |
| `/uploads` | Rota de upload de arquivos |
| `/downloads` | Rota de download de arquivos |

Os métodos HTTP e parâmetros devem ser consultados na implementação de cada rota.

## Deploy

A aplicação será publicada na plataforma Render, utilizando o repositório GitHub.

Comando de inicialização em produção:

```bash
gunicorn app:app
```

## Autor

Nome: Ingridy Bianca Davantel Da Silva e Isadora Cristina de Oliveira

Turma: 2ºA TEC

Disciplina: Desenvolvimento de Aplicações
