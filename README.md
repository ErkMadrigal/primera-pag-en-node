# Mi primera pagina en NodeJs

## interfaz

![Portada del proyecto](assets/img1.png)

![Portada del proyecto](assets/img2.png)

## package.json (descripcion de nuestro proyecto)

* iniciar el proyecto primero con git y despues con npm (npm init --yes y se creara el pakage.json) <br>
 
"name": "primera-pag-en-node",  //nombre del proyecto <br>
  "version": "1.0.0",           //vercion semantica de identificacion del proyecto <br>
  "description": "",            //descripcion de busqueda de npm de nuestro proyecto <br>
  "main": "index.js",           //archivo principal de todo el proyecto <br>
  "scripts": {                  //comandos propios o comando star de arranque <br>
    "start": "node src",        //el comando lo lee Node despues de escribir (npm start)<br>
        //el comando lo lee Node despues de escribir (npm run dev) (nodemon) lo que hace es que se reinicia el servidor una ves modificado el codigo <br>
    "dev": "nodemon src" <br>
  }, <br>
  "keywords": [], <br>
  "author": "", <br>
  "license": "ISC", <br>
  "dependencies": {  // modulos que necesita mi programa <br>
    "ejs": "^3.1.3", <br>
    "express": "^4.17.1", <br>
    "morgan": "^1.10.0" <br>
  }, <br>
  "devDependencies": { // nodulos que no necesitan mi programa <br>
    "nodemon": "^2.0.4" <br>
  } <br>            


  ## modulos de npm 

  * Express  (framework del servidor)
  * EJS       (motor de plantillas)
  * Morgan     (lista en consola de lo que piden los usrs)
  * NodeMond    (npm i nodemond -D  dependencia de desarrollo)
  * bootstrap v5.4

  ## al ejecutarse en otra PC se testea el comando 
  
  * npm install
