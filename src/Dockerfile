# Use a imagem oficial do SQL Server
FROM mcr.microsoft.com/mssql/server:2019-latest

# Defina variáveis de ambiente
ENV ACCEPT_EULA=Y
ENV SA_PASSWORD=YourStrong!Passw0rd
ENV MSSQL_PID=Express

# Exponha a porta padrão do SQL Server
EXPOSE 1433

# Comando para iniciar o SQL Server
CMD ["/opt/mssql/bin/sqlservr"]