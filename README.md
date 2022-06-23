# WebServer + RestServer

Recuerden que deben de ejecutar `npm install` para reconstruir los módulos de Node.

SUPERMODELO DE BACKEND EN NODE

renombremos .example.env -> .env
Instalaciones y configuraciones - Backend
1- Descargar el backend de Node: https://github.com/Klerith/RN-Backend-MERN-CAFE

2- Configuración de Mongo Atlas https://www.mongodb.com/cloud/atlas -> crear un nuevo proyecto 'CafeCluster' aunque lo usemos para un proyecto distinto. Creamos una BDD 'Shared' y en 'Cluster Name' ponemos 'CafeCluster'. Creamos usuario 'roberto`/'Adosat2020' y en IP Address: '0.0.0.0'- Creamos y esperamos unos minutos. Vamos a 'Conectar' y copiamos el enlace para Compass y probamos que se contecta bien. Despues copiamos el enlace para el programa y lo pegamos en la variable MONGODB dentro de .env

3- Configuración de hosting de imágenes - Cloudinary https://cloudinary.com/
roberto.alonso.gandia@gmail.com/Adosat2020@ Dashboard. API Environment Varible (copiamos) y pegamen en .env en la variable de entorno de CLOUDINARY
Vamos a la carpeta del proyecto y yarn start

4- Obtener los servivios en Postmap

https://documenter.getpostman.com/view/343088/TW74j5T2
Desde el archivo en el material adjunto
creamos la variable de entorno url -> http://localhost:8080. Ctrl+S para guardar. Vamos a Collections. arriba a al derecha elegimos el 'entorno' que hemos creado.

