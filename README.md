# async-views

Exemplo de async com django

Este repositório contém exemplos práticos de como implementar views assíncronas no **Django**, utilizando requisições HTTP não bloqueantes com **`httpx`**, rotinas assíncronas com **`asyncio`**, e execução através de um servidor ASGI como o **Uvicorn**.

## Tecnologias Utilizadas

- **Python**
- **Django** (com suporte a views assíncronas)
- **Uvicorn** (servidor ASGI)
- **HTTPX** (cliente HTTP assíncrono)
- **python-dotenv** (gerenciamento de variáveis de ambiente)

## Como Configurar o Projeto

### 1. Clonar o repositório

- git clone (https://github.com/Holandapt/async-views.git)
- cd async-views

# Crie e ative o ambiente virtual:

python -m venv venv

# No Linux/Mac:

source venv/bin/activate

# No Windows:

venv\Scripts\activate

# Instala dependencias

pip install django uvicorn httpx

## Executa projeto:

uvicorn nome_do_projeto.asgi:application --reload
