# Projeto SENAI LH Pets - v1

Este repositório contém o código-fonte e os arquivos necessários para a aplicação **LH Pets**, desenvolvida como parte das atividades do curso no SENAI. O projeto visa a gestão de informações de clientes e vendas para uma loja de pets, utilizando tecnologias web modernas.

## Estrutura do Projeto

- **bin/**: Contém os binários e arquivos compilados necessários para a execução da aplicação.
- **obj/**: Diretório que contém os arquivos de build temporários e outros objetos gerados.
- **wwwroot/**: Pasta que armazena os arquivos estáticos como imagens, JavaScript e CSS utilizados na aplicação.
- **Banco.cs**: Arquivo de implementação para interação com o banco de dados, responsável pelas operações CRUD relacionadas.
- **Clientes.cs**: Model que representa a entidade "Clientes" no sistema, armazenando informações dos clientes.
- **Program.cs**: Arquivo principal para configuração e execução da aplicação, contendo o ponto de entrada do programa.
- **appsettings.Development.json**: Arquivo de configuração para variáveis de ambiente específicas do ambiente de desenvolvimento.
- **appsettings.json**: Arquivo de configuração principal para a aplicação, contendo parâmetros de conexão com o banco de dados e outras definições.
- **senai-codback-ativ2.csproj**: Arquivo de projeto do .NET Core, que define as dependências e estrutura do projeto.
- **vendas.sql**: Script SQL para criação e inserção de dados no banco de dados relacionado ao módulo de vendas.

## Funcionalidades

- **Cadastro de Clientes**: Permite o registro e gerenciamento das informações dos clientes da loja.
- **Gerenciamento de Vendas**: Controle das vendas realizadas, incluindo produtos e serviços oferecidos.
- **Banco de Dados**: Integração com banco de dados relacional, conforme o script `vendas.sql` fornecido.

## Pré-requisitos

Para executar este projeto localmente, você precisará ter:

- [.NET Core SDK](https://dotnet.microsoft.com/download) 6.0 ou superior instalado.
- Um servidor de banco de dados SQL compatível, como o MySQL ou SQL Server.

## Instalação

1. Clone este repositório:

   ```bash
   git clone https://github.com/JefteFontes/Projeto-Senai-LH-Pets-v1.git
   ```
2. Navegue até o diretório do projeto:

   ```bash
   cd Projeto-Senai-LH-Pets-v1
   ```
3. Restaure as dependências:

   ```bash
   dotnet restore
   ```
4. Configure a string de conexão com o banco de dados no arquivo `appsettings.json`.

5. Execute as migrações para o banco de dados utilizando o script SQL `vendas.sql`.

6. Inicie a aplicação:

   ```bash
   dotnet run
   ```
## Uso

- Acesse a aplicação no navegador, normalmente através do endereço [http://localhost:5000](http://localhost:5000).
- Utilize as interfaces fornecidas para cadastrar clientes, gerenciar vendas e consultar informações.
