## Desafio Docker NGINX-NODE Full Cycle

Este projeto é um desafio do curso Full Cycle, que consiste em uma aplicação Node.js com NGINX como proxy reverso e MySQL como banco de dados.

### Descrição

A aplicação realiza as seguintes funções:
- A cada requisição (refresh), um primeiro nome é adicionado à tabela `people` no banco de dados MySQL.
- Após a inserção, todos os nomes cadastrados na tabela são listados no navegador.

### Arquitetura

- **Node.js (Express)**: Aplicação backend que manipula as requisições e interage com o banco de dados.
- **NGINX**: Servidor web que atua como proxy reverso para a aplicação Node.js.
- **MySQL**: Banco de dados utilizado para armazenar os nomes.

### Como Executar o Projeto

1. Certifique-se de ter o Docker e o Docker Compose instalados em sua máquina.
2. Clone este repositório:
   ```sh
   git clone https://github.com/Bidblue/nginx-node-fullcycle.git
3. Inicie os containers com Docker Compose:
   ```sh
   docker-compose up
