## MySQL
Se descarga la imagen oficial  de [mysql image](https://hub.docker.com/_/mysql), esto está todo configurado desde el **docker-compose.yml**

Se requiere clonar el repositorio:
```$console
git clone https://github.com/marioguzmanb/db_connect.git
```
Cambiarse de carpeta al servidor que queremos instalar `mysql`:
```$console
cd mysql/
```
Ejecutar el Docker-Compose para que instale la imagen oficial del servidor en su laptop (Se recomienda cambiar la clave del servidor que se encuentra dentro del archivo **docker-compose.yml**, respetando las reglas que se definen en cada imagen, que contenga mayúscula, números y simbolos)
```$console
docker-compose up
```
Luego tendremos el contenedor con `MySQL` Instalado. Se recomienda tener instalado [DBeaver](https://dbeaver.io) o [Azure Data Studio](https://learn.microsoft.com/en-us/sql/azure-data-studio/download-azure-data-studio?view=sql-server-ver16&tabs=redhat-install%2Credhat-uninstall) para realizar la conexión al servidor.
ma
