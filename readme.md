# Crear un repositorio en GitHub
* Para crear un repositorio local, tenemos crear una carpeta  como cualquiera otra, luego abrimos la consola del git, escribimos, en la ubicación den la carpeta "cd .. 'ubicación de la carpeta' o directamente click derecho en dentro de la carpeta, selecionamos "Git Bash Here".  
  
* Para crear un archivo .md podemos hacerlo desde la consola, escribiendo "touch nombreDelArchivo + la extensión ó simplemente click derecho, crear un nuevo archivo de texto y lo creamos, no nos olvidemos cambiarle el formato a .md
* Cuando hacemos "git status", nos muestra que tenemos nuevos archivos por subir, pero que aún no me hemos hecho nada con ellos, cuando hacemos el "git commit -m \'NombreDelArchivo\'", el archivo se prepara para realizar un push. 

  ![Imágen de git status antes de hacer un commit](https://github.com/Srmanueh01/ejerciciogit/blob/master/captura_1.PNG?raw=true)
  ![Después de haber hecho un commit](https://github.com/Srmanueh01/ejerciciogit/blob/master/captura_2.PNG?raw=true)

* Cuando hacemos un push, lo que hace el git es comprimir el\/los archivo\/s que queremos subir, una vez compreso, los envia a nuestro repositorio.

  ![Ejemplo al realizar un push en git](https://github.com/Srmanueh01/ejerciciogit/blob/master/captura_3.PNG?raw=true)

* Si ejecutamos el comando "git remote -v" la primera vez y no nos sale nada, es por que aun no lo tenememos repositorios.  
    
    ![Ejemplo del comando para agrerar el repositorio](https://github.com/Srmanueh01/ejerciciogit/blob/master/captura_4.PNG?raw=true)


* Tenemos que crear un repositorio en gitHub, una vez creado, más abajo nos sale unas intrucciones con una URL de como tenemos que añadir nuestro repositorio, copiamos la URL y en el git escribimos "git remote add origin InsertarURL".

* Si volvemos a escribir "git remote -v" nos dirá que nuestro repositorio local ya está vilculado con el que tenemos en GitHub.

    ![Ejemplo del comando para agrerar el repositorio](https://github.com/Srmanueh01/ejerciciogit/blob/master/captura_5.PNG?raw=true)

* Para subir los datos a nustro repositorio, recordemos que tenemos que hacer los siguientes pasos: 
  
  + git add . ó el nombre del o los archivos específicos.
  + git commit -m "NombreDeLaVersion".
  + git push

  
* Finalmente comprobamos que todo se ha subido correctamente a nuestro repositorio de GitHub.

    ![Ejemplo del comando para agrerar el repositorio](https://github.com/Srmanueh01/ejerciciogit/blob/master/captura_6.PNG?raw=true)
    
