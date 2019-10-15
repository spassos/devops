### Devops

App Spring Demo mostrando os recursos dos plugins [Flyway](https://flywaydb.org/) e [Liquibase](http://www.liquibase.org/) para versionamento de banco de dados.

Instalar o [Docker](https://www.docker.com/) e rodar o comando `docker run`

`docker run -e 'ACCEPT_EULA=Y' -e 'SA_PASSWORD=D3mo1234567890' -p 1433:1433 -d mcr.microsoft.com/mssql/server:2017-latest`

Criar os banco de dados para a demo:

```sql
CREATE DATABASE demodevops;
GO
CREATE DATABASE demodevops_2;
```
