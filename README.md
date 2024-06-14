# Prefect Rick and Morty Project

### 📋 Objetivo do Projeto
- O objetivo deste projeto é explorar o uso do Prefect para orquestrar tarefas de consumo de uma API externa, mostrando como lidar com timeouts e retries. Além disso, o projeto busca integrar esses dados consumidos a um banco de dados utilizando uma API RESTful, aplicando o padrão de arquitetura limpa (Clean Architecture) para garantir uma clara separação de responsabilidades e boas práticas de desenvolvimento.

### 🛠️ Tecnologias Usadas
- Python: 3.7
- Prefect: 2.x
- FastAPI: 0.95.x
- Uvicorn: 0.22.x
- Requests: 2.28.x
- Pydantic: 1.10.x

### 📂 Estrutura do Projeto
O projeto é estruturado utilizando o padrão Clean Architecture, garantindo uma separação clara de responsabilidades e facilitando a manutenção e escalabilidade do código. Abaixo está um resumo das principais pastas e arquivos:

### 🚀 Como Executar

- Clone o Repositório:
```sh
git clone https://github.com/seu-usuario/prefect-rick-and-morty.git
cd prefect-rick-and-morty
```

- Crie e Ative um Ambiente Virtual:
```sh
python -m venv venv
source venv/bin/activate  # No Windows use `venv\Scripts\activate`
```

- Instale as Dependências:
```sh
pip install -r requirements.txt
```

- Execute o Flow do Prefect:
```sh
prefect run -p app/flows/rick_and_morty_flow.py
```

- Inicie a Aplicação FastAPI:
```sh
uvicorn main:app --reload
```

### Acesse a API:

A documentação interativa estará disponível em http://127.0.0.1:8000/docs.


# 👩‍💻 Desenvolvedora
Este projeto foi desenvolvido por 
```sh
    - Laysa Santana dos Santos, Desenvolvedora Backend.
```
