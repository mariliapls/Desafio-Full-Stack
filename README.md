# Desafio-Full-Stack
Este projeto é uma aplicação Django simples que exibe uma página com a mensagem "Hello World".

Pré-requisitos
Python 3.6 ou superior instalado

pip instalado

(Opcional, recomendado) Ambiente virtual Python (venv)

Passos para rodar a aplicação
Clone este repositório

bash
Copiar
Editar
git clone <URL_DO_REPOSITORIO>
cd meuprojeto
(Opcional) Crie e ative um ambiente virtual

No Windows:

bash
Copiar
Editar
python -m venv venv
venv\Scripts\activate
No macOS/Linux:

bash
Copiar
Editar
python3 -m venv venv
source venv/bin/activate
Instale as dependências

bash
Copiar
Editar
pip install django
Aplique as migrações do banco de dados

bash
Copiar
Editar
python manage.py migrate
Execute o servidor

bash
Copiar
Editar
python manage.py runserver
Abra o navegador

Acesse: http://127.0.0.1:8000/

Você verá a mensagem:

nginx
Copiar
Editar
Hello World
Estrutura do projeto
meuprojeto/ — pasta do projeto Django

hello/ — app com a view "Hello World"

manage.py — arquivo para rodar comandos Django
