# Actividad-clase-Deployment-app

Para descargar el repositorio hay que introducir el siguiente comando en el terminal:
```
git clone https://github.com/aitorseguramateos/Actividad-clase-Deployment-app.git
```

Creamos la imagen:
```
docker build -t mi-web .
```

Arrancamos el contenedor:
```
docker run -d -p 8080:80 mi-web
```
