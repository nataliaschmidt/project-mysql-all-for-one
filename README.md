# All For One

Este projeto consiste em uma série de desafios nos quais devemos criar queries SQL para encontrar, filtrar e manipular informações no banco de dados Northwind.

A estrutura do projeto foi fornecida pela Trybe e os requisitos foram implementados nos arquivos desafioN.sql, localizados na raiz do projeto.

Utilizei o Workbench como ferramenta visual para auxiliar na criação e execução das queries.

## Tecnologias Utilizadas
<hr>

- SQL
- Docker

## Instruções
<hr>

- Clone este repositório para o seu ambiente de desenvolvimento local.

```bash
git clone git@github.com:nataliaschmidt/project-mysql-all-for-one.git
```
- Antes de começar, seu docker-compose precisa estar na versão 1.29 ou superior.

- Execute o seguinte comando para rodar os serviços node e db:
```bash
docker-compose up -d
```
- Esses serviços irão inicializar um container chamado all_for_one e outro chamado all_for_one_db.
- A partir daqui você pode rodar o container all_for_one via CLI ou abri-lo no VS Code. Use o comando:
```bash
docker exec -it all_for_one bash
```
- Agora você tem acesso ao terminal interativo do container criado pelo compose.