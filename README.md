# landingPage
this is a landing page for maniak 

# Node js
Es necesario tener instalado node en tu maquina
# NPM
NPM utiliza el archivo package.json para almacenar todos los datos relevantes a nuestra aplicación, asi que es necesario tenerlo instalado, lo haremos con el comando:
![npm install](/images/npm.jpg?raw=true "Optional Title")
# Gulp-sass
La landing está realizada con sass, es necesario tener el modulo Gulp-sass, lo haremos con el siguiente comando:
![gulp watch](/images/gulpSass.jpg?raw=true "Optional Title")
# Gulp
El archivo a modificar para cambio de estilos es style.scss, el cual se compila ejecutando gulp watch (gulp watch se instala como previamente se instaló gulp-sass) de y lo ejecutaremos de la siguiente forma:
![gulp watch](/images/watchimg.jpg?raw=true "Optional Title")
# Gulpfile
El archivo Gulpfile.js contiene las rutas necesarias para dirigir todos los archivos sass a css, asi mismo como la tarea gulp watch, esta archivo es muy sensible, favor de abstener su modificación para la correcta compilación de los archivos.
![gulpfile](/images/gulpfile.jpg?raw=true "Optional Title")
