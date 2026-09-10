# Controle Financeiro API

API desenvolvida com **FastAPI** para gerenciamento de movimentações financeiras.

## Tecnologias

- Python 3.11+
- FastAPI
- Uvicorn
- SQLAlchemy
- Pytest

---

## Estrutura do Projeto

```
controle-financeiro/
│
├── app/
│   ├── routes/
│   ├── database.py
│   ├── main.py
│   ├── models.py
│   └── schemas.py
│
├── tests/
├── requirements.txt
├── Dockerfile
└── README.md
```

---

# Como executar o projeto

## 1. Clonar o repositório

```bash
git clone <link-do-repositorio>
```

Entre na pasta do projeto:

```bash
cd controle-financeiro
```

---

## 2. Criar um ambiente virtual

### Windows

```bash
python -m venv venv
```

Ative o ambiente:

```bash
venv\Scripts\activate
```

### Linux/Mac

```bash
python3 -m venv venv

source venv/bin/activate
```

---

## 3. Instalar as dependências

```bash
pip install -r requirements.txt
```

Caso o Uvicorn não esteja instalado:

```bash
pip install uvicorn
```

Ou instale o pacote completo do FastAPI:

```bash
pip install "fastapi[standard]"
```

---

## 4. Executar a aplicação

```bash
python -m uvicorn app.main:app --reload
```

Após iniciar, a API estará disponível em:

```
http://127.0.0.1:8000
```

---

## Documentação da API

Swagger UI

```
http://127.0.0.1:8000/docs
```

Redoc

```
http://127.0.0.1:8000/redoc
```

---

# Executando os testes

```bash
pytest
```

Caso queira visualizar mais detalhes:

```bash
pytest -v
```

---

# Autores
Enzo Nardelli, Letícia de Souza e João Gabriel Costa.

Projeto desenvolvido para fins de estudo e prática utilizando FastAPI.
