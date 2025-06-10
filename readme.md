# Projeto de Gerenciamento de Banco de Dados

Este é um projeto Python focado na gestão de um banco de dados, utilizando SQLAlchemy para abstração e interação. A estrutura abrange desde a configuração inicial do banco até a definição de modelos de dados, procedimentos e triggers.

## Visão Geral das Funcionalidades

*   **Provisionamento de Banco de Dados**: Inicializa e configura um banco de dados SQLite (`hospital.db`).
*   **Modelagem de Dados**: Define o esquema do banco de dados através de modelos SQLAlchemy, facilitando a manipulação de tabelas e relacionamentos.
*   **Lógica de Banco de Dados**: Incorpora procedimentos e triggers para automatizar e otimizar operações no nível do banco de dados.

## Stack Tecnológica

*   **Python**: Linguagem de desenvolvimento principal.
*   **SQLAlchemy**: ORM (Object Relational Mapper) que simplifica a interação com o banco de dados, permitindo a manipulação de dados como objetos Python.
*   **SQLite**: Banco de dados leve e embarcado, ideal para prototipagem e aplicações que não exigem um servidor de banco de dados dedicado (`hospital.db`).

## Setup e Instalação

Para colocar o projeto em funcionamento localmente, siga os passos abaixo:

1.  **Clonagem do Repositório**:
    ```
    git clone <URL_DO_SEU_REPOSITORIO>
    cd <nome_da_pasta_do_projeto>
    ```

2.  **Configuração do Ambiente Virtual**:
    Recomenda-se o uso de um ambiente virtual para isolar as dependências do projeto:
    ```
    python -m venv .venv
    # Windows
    .venv\Scripts\activate
    # macOS/Linux
    source .venv/bin/activate
    ```

3.  **Instalação de Dependências**:
    As dependências do projeto estão listadas em `requirements.txt`:
    ```
    pip install -r requirements.txt
    ```

## Execução do Projeto

Após a instalação das dependências, execute o script principal para criar o banco de dados e as tabelas:

```
python app/main.py
