# Projeto 2023.2-Grupo03

## Descrição

Este projeto utiliza o MkDocs para criar uma página de documentação local. Siga as instruções abaixo para configurar e executar o projeto em sua máquina local.

## Pré-requisitos

- Certifique-se de que você tem Python instalado em sua máquina. Se não tiver, você pode baixá-lo [aqui](https://www.python.org/downloads/).
- Você também precisará do gerenciador de pacotes Python `pip`. Ele geralmente é instalado junto com o Python.

## Instalação

### Instalar MkDocs

1. Abra o terminal e execute o seguinte comando para instalar o MkDocs.

    ```bash
    pip install mkdocs
    ```

## Execução

### Construir o Projeto

1. Utilize o comando abaixo para construir os arquivos estáticos do projeto.

    ```bash
    mkdocs build
    ```
    Este comando irá gerar uma pasta `site` contendo todos os arquivos HTML, CSS e outros necessários para a visualização da documentação.

### Servir o Projeto Localmente

1. Execute o seguinte comando para iniciar um servidor local.

    ```bash
    mkdocs serve
    ```
    Este comando inicia um servidor web local para que você possa visualizar a documentação em seu navegador. Normalmente, a URL será `http://127.0.0.1:8000/`.

