# Tasks-Flask-CRUD

## Descrição

Este projeto é uma API REST construída com Flask para gerenciar tarefas. A API permite realizar operações CRUD (Criar, Ler, Atualizar, Deletar) em tarefas. Além disso, o projeto inclui testes automatizados usando pytest para garantir a qualidade e integridade das funcionalidades implementadas.

## Funcionalidades

A API possui as seguintes funcionalidades:

- **Criar uma nova tarefa**: Permite adicionar uma nova tarefa à lista de tarefas.
- **Listar todas as tarefas**: Retorna uma lista de todas as tarefas.
- **Visualizar uma tarefa específica**: Retorna os detalhes de uma tarefa específica, dado o seu ID.
- **Atualizar uma tarefa**: Permite modificar os detalhes de uma tarefa existente.
- **Deletar uma tarefa**: Remove uma tarefa da lista de tarefas através do ID.

## Tecnologias Utilizadas

- **Flask**: Utilizado para a criação da API.
- **Pytest**: Utilizado para a automação dos testes da API.

## Instalação

Para configurar e executar este projeto localmente, siga os passos abaixo:

1. Clone o repositório:
   
   ```sh
   https://github.com/LeticiaCastelo/tasks-flask-crud.git
3. Com o ambiente virtual ativado, instale as dependências do projeto usando o comando:
   
    ```bash
    pip install -r requirements.txt
    ```
## Testes Automatizados

Os testes automatizados foram implementados com o pytest. Para executar os testes, utilize o seguinte comando:
```bash
pytest tests.py -v
```
