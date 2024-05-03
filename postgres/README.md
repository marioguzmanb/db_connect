## Postgres
Se descarga la imagen oficial  de [postgres image](https://hub.docker.com/_/postgres), esto está todo configurado desde el **docker-compose.yml**

Se requiere clonar el repositorio:
```$console
git clone https://github.com/marioguzmanb/db_connect.git
```
Cambiarse de carpeta al servidor que queremos instalar `Postgres`:
```$console
cd postgres/
```
Ejecutar el Docker-Compose para que instale la imagen oficial del servidor en su laptop (Se recomienda cambiar la clave del servidor que se encuentra dentro del archivo **docker-compose.yml**, respetando las reglas que se definen en cada imagen, que contenga mayúscula, números y simbolos)
```$console
docker-compose up
```
Luego tendremos el contenedor con `Postgres` Instalado. Se recomienda tener instalado [DBeaver](https://dbeaver.io) y crear la conexión.