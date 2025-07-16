# Jogoteca

Projeto web simples desenvolvido em Flask para gerenciar uma coleção de jogos.  
Funcionalidades incluem cadastro, edição e remoção de jogos, upload de imagens para capas, sistema básico de autenticação (login/logout) e interface responsiva com Bootstrap.  

Tecnologias usadas: Python 3.13, Flask, Flask-WTF, Flask-Bcrypt, SQLAlchemy, MySQL e Bootstrap.

## Como Rodar o Projeto

1. Clone o repositório:  
```
git clone https://github.com/raiego/projeto-jogoteca-flask-python.git
cd projeto-jogoteca-flask-python
```

2. Crie e ative o ambiente virtual:
No Windows:
```
python -m venv .venv
.venv\Scripts\activate
```
No Linux/macOS
```
python3 -m venv .venv
source .venv/bin/activate
```
3. Instale as dependências:
```
pip install -r requirements.txt
```
4. Configure o banco de dados MySQL:

Garanta que o MySQL esteja instalado e rodando.

Ajuste o arquivo prepara_banco.py com suas credenciais, se necessário.

Execute o script para criar o banco e as tabelas:
```
python prepara_banco.py
```

5. Execute o projeto:
```
flask run
```

6. Acesse a aplicação no navegador:
```
http://127.0.0.1:5000
```

