# landingPage
This is a landing page for maniak 
# Node js
Es necesario tener instalado node en tu maquina
# NPM
NPM utiliza el archivo package.json para almacenar todos los datos relevantes a nuestra aplicación, asi que es necesario tenerlo instalado, lo haremos con el comando:
![npm install](/images/npm.jpg?raw=true "Npm Install")
# Gulp-sass
La landing está realizada con sass, es necesario tener el modulo Gulp-sass, lo haremos con el siguiente comando:
![gulp sass](/images/gulpSass.jpg?raw=true "Gulp-Sass")
# Gulp
El archivo a modificar para cambio de estilos es style.scss, el cual se compila ejecutando gulp watch (gulp watch se instala como previamente se instaló gulp-sass) y lo ejecutaremos de la siguiente forma:
![gulp watch](/images/watchimg.jpg?raw=true "Gulp Watch")
# Gulpfile
El archivo Gulpfile.js contiene las rutas necesarias para dirigir todos los archivos sass a css, asi mismo como la tarea gulp watch, esta archivo es muy sensible, favor de abstener su modificación para la correcta compilación de los archivos.
![gulpfile](/images/gulpfile.jpg?raw=true "Gulpfile")
# Estructura css
El archivo principal para la modificacion de estilos es style.scss, el archivo _mixins.scss contiene varias instrucciones que son optativas y necesarias, de ahi se desprende la incoporación de las fuentes, el reemplazamiento de estilos propios de bootstrap y un "range bar" que se modificó para una de las secciones.