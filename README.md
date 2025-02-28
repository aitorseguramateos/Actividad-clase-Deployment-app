# Actividad-clase-Deployment-app

Instalamos los paquetes requeridos:
```
sudo apt install docker-compose docker git
```

A continuación procederemos descargar el repositorio. Para ello hay que introducir el siguiente comando en el terminal:
```
git clone https://github.com/aitorseguramateos/Actividad-clase-Deployment-app.git
```

Seguidamente nos ubicaremos en el terminal y descomprimiremos el archivo `.zip`.
```
cd Actividad-clase-Deployment-app
```
```
unzip M08-WEB-APP.zip
```

Finalmente nos ubicaremos en el directorio que acabamos de descomprimir y desplegaremos el contenedor.
```
cd M08-WEB-APP
```
```
docker-compose up --build
```
