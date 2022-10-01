
<div>
<h1 align="center"><img src="./src/public/img/task.png"> Project: Task Notepad</h1>
&nbsp;


<p><img src="./src/public/img/no_task.png""></p>
</div>
&nbsp;

---



 <h3 align="center"> 💻Trabajo Práctico Final - Curso Full Stack Avanzado - UTN</h3>
<h5 align="center">Task Notepad es una aplicación web que nos permite crear, leer, actualizar y borrar tareas.</h5>


&nbsp;

---

<p align="center">👩‍💻 Hecho  por la alumna:</p>

```GitHub profil ↓```
<ul>
        <li><a href="https://github.com/monicapajon" target="_blank">Mónica Pajón</a></li>
</ul>
&nbsp;

---
### ¿Qué programas necesitas tener instalados?
<p>Para que funcione ésta aplicación necesitas tener instalado los siguientes programas: Git, Visual Studio Code, NodeJS y MongoDB.</p>
&nbsp;

---
### Enviroment variables
<p>También puedes añadir las siguientes variables de entorno en el archivo .env:</p>
<p>MONGODB_URI</p>
<p>PORT</p>
&nbsp;

---
### Instalación (Manual)
<p>Primero necesitas abrir una terminal y ejecutar el comando “mongod” que arranca el servidor de mongodb, y la dejas abierta que corra.
<p>Abres el programa Visual Studio Code, y ejecutas los siguientes comandos:</p>
<p>git clone https://github.com/monicapajon/taskNotepad.git<p>
<p>cd taskNotepad</p>
<p>npm install</p>
<p>npm run dev</p>

<p>Abres el navegador y escribes: http://localhost:3000/, y listo, puedes empezar a usar la aplicación “Task Notepad”.</p>

&nbsp;

---


<p>💪 Se han utilizado dependencias, frameworks y base de datos   aprendidos en éste curso, eligiendo NodeJS y Mongodb para ésta aplicación.</p>
&nbsp;

---

&nbsp;

 
<h3 align="center">📝 Contenido</h3>

   
&nbsp;

<h3 align="center">Lenguajes y Herramientas</h3>
 HTML, CSS, JavaScript, Node JS, Bootstrap, Express, Express-Handlebars, Mongoose, Morgan, Nodemon, Mongodb.
 <p>Express es un framework escrito en JS, se utilizó el modelo de plantilla Handlebars.</p>
 <p>Mongoose permite conectarnos y modelar los datos dentro de la base de datos.</p>
 <p>Morgan es un paquete que no es esencial para nuestra aplicación pero nos va a permitir ver por consola las peticiones que van llegando.</p>
 <p>Se utilizó Babel (compilador de JS) que compila código nuevo a versiones anteriores a JS.</p>
 <p>Nodemon envuelve la aplicación Node, vigila el sistema de archivos y reinicia automáticamente el proceso.</p>

    
&nbsp;

 <h3 align="center">🎛 Estructura del Proyecto</h3>
 <p>1- Los archivos principales se encuentran dentro de la carpeta src.</p>
 <p>2- El archivo .env define las variables de entorno.</p>
 <p>3- index.routes.js define los endpoints que serán consumidos desde el cliente.</p>
 <p>4- El archivo Task.js (dentro de la carpeta models) establece el modelo de datos con Mongoose.</p>
 <p>5- En la carpeta css se definen los estilos.</p>
 <p>6- El archivo main.hbs tiene toda la estructura del HTML5.</p>
 <p>7- Handlebars me crea una carpeta partials en views.</p>
 <p>8- Dentro de partials tengo archivos que contienen formularios por donde el usuario ingresa los datos y la tabla por donde se muestran los datos que devuelve mi Base de Datos.</p>
 <p>9- El archivo app.js es uno de los archivos mas importantes de la aplicación, puesto que es el primer componente que se cargará.</p>









   
&nbsp;

<h3 align="center">🎛 Funcionalidades Principales</h3>
 <p>Task Notepad es una aplicación web que nos permite crear, leer, actualizar y borrar tareas.</p>
<p> Posee una columna en la cual la aplicación coloca automáticamente el número de tarea.</p>
<p>Además se le agregó un botón que permite seleccionar la opción "DONE" (tarea realizada) o "UNDONE" (tarea incompleta).</p> 
&nbsp;

 
&nbsp;

``` 
                                                  ✔️
```
 
&nbsp;

<p align="center">Task Accomplished</p>
<p align="center"><img src="https://media.giphy.com/media/7JEPMRdfPLfq1sjZUJ/giphy-downsized-large.gif" width="300px"></p>
 
 
&nbsp;


---

