# Sistema de Controle de Estoque

Este projeto é um **Sistema de Controle de Estoque** desenvolvido em Python, projetado para gerenciar produtos, fornecedores e pedidos de reposição. Ele permite o registro de produtos, controle de quantidades disponíveis e alertas de reposição quando o estoque atingir um limite crítico.

## Funcionalidades

- Registro de novos produtos
- Controle de quantidade em estoque
- Gerenciamento de fornecedores
- Relatórios sobre produtos em falta

## Instalação

### Pré-requisitos

- Python 3.8 ou superior
- Biblioteca `pip` para gerenciar as dependências

### Passos para instalar

1. Clone este repositório:

    ```bash
    git clone https://github.com/usuario/sistema-controle-estoque.git
    ```

2. Acesse a pasta do projeto:

    ```bash
    cd sistema-controle-estoque
    ```

3. Instale as dependências listadas no `requirements.txt`:

    ```bash
    pip install -r requirements.txt
    ```

4. Execute o sistema:

    ```bash
    python src/main.py
    ```

## Testes

Os testes podem ser executados com `unittest`:

```bash
python -m unittest discover tests/
