# AllFood_Back

Back-end desenvolvido em Python para um site de restaurantes.

## Descrição

O projeto AllFood_Back é a parte de back-end de uma aplicação destinada a gerenciar informações de restaurantes.

## Tecnologias Utilizadas

- **Python**: Linguagem de programação principal utilizada no desenvolvimento do back-end.
- **Django**: Framework web em Python que facilita a criação de aplicações web robustas e escaláveis.
- **Docker**: Ferramenta de containerização utilizada para criar ambientes isolados e consistentes para a aplicação.
- **Docker Compose**: Utilizado para orquestrar os containers Docker, facilitando o gerenciamento de ambientes complexos.

## Estrutura do Projeto

A estrutura principal do projeto é composta pelos seguintes diretórios e arquivos:

- **media_root/**: Diretório destinado ao armazenamento de arquivos de mídia da aplicação.
- **restaurantes/**: Diretório que contém a aplicação principal relacionada ao gerenciamento de restaurantes.
- **setup/**: Diretório que possivelmente contém scripts de configuração e instalação.
- **.gitignore**: Arquivo que especifica quais arquivos ou pastas devem ser ignorados pelo Git.
- **Dockerfile**: Arquivo de configuração para a criação da imagem Docker da aplicação.
- **docker-compose.yml**: Arquivo de configuração do Docker Compose para orquestração dos containers.
- **img.jpeg**: Arquivo de imagem que pode estar relacionado à documentação ou à interface da aplicação.
- **manage.py**: Script de gerenciamento do Django para execução de comandos administrativos.
- **requirements.txt**: Arquivo que lista as dependências Python necessárias para o projeto.

## Pré-requisitos

Certifique-se de ter as seguintes ferramentas instaladas em seu ambiente de desenvolvimento:

- [Python](https://www.python.org/downloads/): Versão compatível com o Django utilizado no projeto.
- [Docker](https://docs.docker.com/get-docker/): Para criar e gerenciar containers.
- [Docker Compose](https://docs.docker.com/compose/install/): Para orquestrar os containers Docker.

## Como Executar o Projeto

1. **Clone o repositório**:

   ```bash
   git clone https://github.com/Andre-StudioNerd/AllFood_Back.git
   cd AllFood_Back
   ```

2. **Construa e inicie os containers Docker**:

   ```bash
   docker-compose up --build
   ```

   Este comando irá construir as imagens Docker conforme especificado no `Dockerfile` e iniciar os serviços definidos no `docker-compose.yml`.

3. **Acesse a aplicação**:

   Após a inicialização bem-sucedida, a aplicação estará disponível no endereço `http://localhost:8000/` ou conforme configurado no `docker-compose.yml`.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests com melhorias, correções de bugs ou novas funcionalidades.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
