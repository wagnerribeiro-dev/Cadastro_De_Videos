# Projeto Cadastro de Vídeo

Este projeto é uma API para gerenciamento de vídeos, desenvolvido em Node.js, utilizando um banco de dados relacional. O deploy foi realizado utilizando o serviço Render.

## Tecnologias Utilizadas

- Node.js
- FASTIFY
- PostgreSQL
- Render (deploy)

## Requisitos

- Node.js v14 ou superior
- PostgreSQL v12 ou superior

## Instalação

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/projeto-video.git
```

2. Navegue até o diretório do projeto:

```bash
cd projeto-video
```

3. Instale as dependências:

```bash
npm install
```

4. Configure as variáveis de ambiente:

Crie um arquivo `.env` na raiz do projeto com as seguintes variáveis de ambiente:

```env
DB_HOST=<seu_host_de_banco_de_dados>
DB_USER=<seu_usuario_de_banco_de_dados>
DB_PASSWORD=<sua_senha_de_banco_de_dados>
DB_NAME=<nome_do_seu_banco_de_dados>
PORT=3000
```

5. Execute as migrações do banco de dados:

```bash
npx sequelize-cli db:migrate
```

6. Inicie o servidor:

```bash
npm start
```

O servidor estará rodando em `http://localhost:3000`.

## Endpoints

Abaixo estão listados alguns endpoints da API:

- `GET /videos`: Lista todos os vídeos.
- `POST /videos`: Cria um novo vídeo.
- `GET /videos/:id`: Retorna um vídeo específico pelo ID.
- `PUT /videos/:id`: Atualiza um vídeo específico pelo ID.
- `DELETE /videos/:id`: Remove um vídeo específico pelo ID.

## Deploy

O deploy deste projeto foi realizado no Render. Para acessar a aplicação em produção, utilize o seguinte URL:

[https://seu-projeto-no-render.onrender.com](https://seu-projeto-no-render.onrender.com)

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
```

