DISTRIBUCION DE LAS CARPETAS Y ARCHIVOS PRINCIPALES
===================================================

src va a tener todo el codigo (front y back)
src/index.js es el archivo de node js
src/database.js conecta a la base de datos
src/routes/ rutas para que la app de front end va a acceder al servidor
src/routes/task.routes.js define las operaciones que va a realizar el servidor a traves de URLs
src/models/ define que datos voy a almacenar en la base de datos
src/models/task.js diseño del esquema de datos
src/public/ Contiene los archivos estaticos (imagenes, fuentes, audio, css) para enviarlos al front end
	           Es tambien donde ira el codigo convertido de react
src/app/ contiene el codigo de react

!!! I M P O R T A N T E !!!!
Añadir en windows -> configuracion avanzada -> variables de entorno -> agregar: Node y la ruta donde esta instalado nodejs (c:\archivos de programa\nodejs)

----------------------

Inicio de la configuracion (Solo una vez al iniciar el proyecto)

npm init --yes para inicializar el proyecto
npm install express
npm install --save nodemon
npm install morgan //Permite ver por consola las peticiones al servidor
npm install mongoose //Permite conectar a la base de datos y definir los modelos de la DB



***Instalar en Windows "Robo studio 3T" para ver graficamente la DB
