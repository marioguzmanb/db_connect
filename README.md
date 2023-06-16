# Conexiones a las diferentes bases de datos
Este repositorio nos ayudará a como configurar las diferentes bases de datos a través de una imagen de [docker]('https://www.docker.com/products/docker-desktop/')
# Estructura del repositorio
.gitignore
postgres/
  - docker-compose.yml
sql-server/
  - docker-compose.yml
mariadb/
  - docker-compose.yml
mysqlls
  - docker-compose.yml

Se requiere clonar el repositorio:
```$console
git clone https://github.com/marioguzmanb/db_connect.git
```
Cambiarse de carpeta al servidor que queremos instalar, por ejemplo SQL Server:
```$console
cd sql-server/
```
Ejecutar el Docker-Compose para que instale la imagen oficial del servidor en su laptop (Se recomienda cambiar la clave del servidor que se encuentra dentro del archivo **docker-compose.yml**, respetando las reglas que se definen en cada imagen, que contenga mayúscula, números y simbolos)
```$console
docker-compose up
```
Luego tendremos el contenedor con SQL Server Instalado. Se recomienda tener instalado [DBeaver](https://dbeaver.io) o [Azure Data Studio](https://learn.microsoft.com/en-us/sql/azure-data-studio/download-azure-data-studio?view=sql-server-ver16&tabs=redhat-install%2Credhat-uninstall) para realizar la conexión al servidor.

## Postgres
Se descarga la imagen oficial  de [postgres image](https://hub.docker.com/_/postgres)
## Sql Server
Se descarga la imagen oficial  de [sql-server image](https://hub.docker.com/_/microsoft-mssql-server)
## MySQL
Se descarga la imagen oficial  de [mysql image](https://hub.docker.com/_/mysql)
## MariaDB
Se descarga la imagen oficial  de [mariadb image](https://hub.docker.com/_/mariadb)
