<img src="https://1000logos.net/wp-content/uploads/2018/11/GitHub-logo.png"  width="200px" height="150px">



# LINEAS DE COMANDO PARA MAJ}NEJAR NUESTROS REPOSITORIOS DE GIT:<br>

todo los comandos deran utilizados mediante la terminal de visual studio code:<br>

1.- git init <br>
se encarga de iniciar todos los archivos necesarios de git dentro de nuestra carpeta local.<br> 

2.- git add . <br>
añade o toma una captura de todos los elementos que se encuentran dentro de nuestro proyecto<br> 
*esto se tiene que hacer cada que vallamos a guardar cambios*<br>

4.- git commit -m <br>
este comando realiza un comentario dentro de nuestro cambio que vamos a realizar mediante el comando commit

# SE NOS PEDIRAN NUESTRO DATOS DE ACCESO DE LA CUENTA DE GITHUB O PODEMOS AGREGARLOS NOSOTROS DIRECTAMENTE CON LOS SIGUIENTES COMANDOS <br>

1.- git config --global user.name "nombre_usuario"<br>
*aqui escribiremos  nuestro usuario de github*<br>

2.- git config --global user.email johndoe@example.com<br>
*aqui escribiremos nuestro email*


*NOTA: MUCHAS VECES SE NOS ABRIRA UNA VENTANA PARA LOGUEARNOS DE MANERA GRAFICA CON NUESTRA CUENTA DE GITHUB, ES MEJOR DE ESTA MANERA YA QUE SE EVITAN CONFUSIONES* <BR>

# COMANDOS UTILES PARA LA ADMINISTRACION DE NUESTRO REPOSITORIO

1.- git checkout -- .<br>
Reconstruye nuestro proyecto a una version anterior del ultimo commit 
*esto es muy util por si nos equivocamos*

2.- git log  <br>
*revisa todos los logs y sus hash*<br>

3.- git commit --amend  <br>
*corrige commits mal escritos*<br>

4.- git checkout -b rama-heroes  <br>
*para crear una rama nueva y no afectar la principal.*<br>

5.- git checkout master <br>
*revisa los archivos dentro de la rama master*

<br><br>
# AGREGAR UN REPOSITORIO DE GITHUB A NUESTRO PROYECTO LOCAL (ENLAZARNOS AL REPOSITORIO REMOTO)<br>

1.- git remote add origin (link del repositorio que nos provee github) <br>  
*añade el origen de donde vamos a importar y exportare nuestro proyecto remoto*<br>

2.- git branch -M main<br>
*agregarmos los archivos a la rama principal o MAIN* <br>


3.- git push -u origin main<br>
*Hacemos un PUSH para enviar los cambios locales a nuestro repositorio remoto en la rama MAIN*