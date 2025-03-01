# CRUD de Pessoa em C# com ASP.NET Core e SQLite
<br/>
Este projeto é uma API REST para cadastro de pessoas, utilizando C#, ASP.NET Core e SQLite como banco de dados.
<br/>
<br/>

### 🔧 Tecnologias Utilizadas
    - C#
    - ASP.NET Core Minimal API
    - Entity Framework Core
    - SQLite
    - Swagger
<br/>

### 📂 Organização do Projeto
    Person/
    - Data/               # Contexto do Banco de Dados
    - Migrations/         # Arquivos de Migração
    - Models/             # Modelos de Dados
    - Routes/             # Rotas da API
    - appsettings.json    # Configuração da aplicaçãoProgram.cs         
    - Program.cs          # Inicialização da aplicação
    - person.Sqlite       # Banco de Dados SQLite
<br/>

### 🗂️ Banco de Dados
Este projeto utiliza SQLite com Entity Framework Core. O arquivo do banco é criado na raiz do projeto como person.Sqlite.
<br/>
<br/>

### 🔍 Observações
- Este projeto foi criado para estudos de C# e ASP.NET Core.
- A funcionalidade de desativação apenas altera o nome da pessoa para "desativado".
- Utiliza Minimal APIs.

### 📄 Licença
Este projeto está licenciado sob os termos da MIT License.
