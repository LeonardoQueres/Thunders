##Projeto Thunders - Docker - .NET - C# - SQL SERVER

- Criar banco da dados SQL SERVER

`docker pull mcr.microsoft.com/mssql/server:2022-latest`

`docker run -e 'ACCEPT_EULA=Y' -e 'SA_PASSWORD=123456' -p 1433:1433 --name MDNsqlserver -d mcr.microsoft.com/mssql/server:2022-latest `

- Criar e iniciar contêineres
  
`docker-compose up -d`

