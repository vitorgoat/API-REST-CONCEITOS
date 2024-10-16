# 🎬 API REST de Filmes

## 📖 Descrição

Esta é uma **API REST** para gerenciamento de filmes, permitindo a criação, leitura, atualização e exclusão de informações sobre filmes. A API foi desenvolvida seguindo os princípios REST e utiliza o **AutoMapper** para simplificar a transformação de objetos.

## 🛠 Tecnologias Utilizadas

- **.NET Core**: Framework para desenvolvimento da API.
- **AutoMapper**: Biblioteca para mapeamento de objetos.
- **Entity Framework Core**: ORM para interação com o banco de dados.
- **SQL Server**: Banco de dados utilizado.

## 🌐 Conceitos HTTP Aplicados

A API implementa os seguintes métodos HTTP:

- **GET**: Recupera informações do servidor.
- **POST**: Envia dados ao servidor para criar um novo recurso.
- **PUT**: Atualiza um recurso existente no servidor.
- **DELETE**: Remove um recurso do servidor.

### 📚 Exemplos de Endpoints

| Método | Endpoint                 | Descrição                            |
|--------|--------------------------|-------------------------------------|
| GET    | `/api/filmes`           | Retorna uma lista de filmes.       |
| GET    | `/api/filmes/{id}`      | Retorna os detalhes de um filme.   |
| POST   | `/api/filmes`           | Cria um novo filme.                |
| PUT    | `/api/filmes/{id}`      | Atualiza as informações de um filme.|
| DELETE | `/api/filmes/{id}`      | Remove um filme.                   |

## 🔄 AutoMapper

O **AutoMapper** foi utilizado para facilitar a transformação de DTOs (Data Transfer Objects) para entidades e vice-versa, tornando o código mais limpo e reduzindo a duplicação.

