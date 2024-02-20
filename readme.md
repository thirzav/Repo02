# Principales comandos git  
  
##  Moverse por las carpetas:
**pwd** - print working directory, para ver dónde nos posicionamos.  
**ls** - para ver el listado de directorios de donde nos encontramos.  
**cd** - change directory, para moverse entre las carpetas.  
**cd ..** - para ir atrás en las carpetas.
  
  ## Crear carpetas y archivos:  
  **mkdir** ***"nombreCarpeta"*** - para crear una carpeta nueva en el directorio donde te encuentras.  
  **touch** ***"nombreArchivo.formato"*** - para crear un archivo nuevo dentro de la carpeta donde te encuentras.  
  **git init** - para empezar a trabajar con repositorio local.  
  **code \.** - para abrir la carpeta donde nos encotramos en Visual Studio Code.  

  ## Comprobación:  
  **git log** - para ver los commits que hemos hecho hasta el momento, incluye información del creador, fecha y el mensaje.  
  **git status** - enseña dónde se encuentra cada fichero.  

## Configurar git usuario y email:  
**git config --global user.name** ***"nombre"*** - para introducir el nombre del creador de los commits en este repositorio local.  
**git config --global user.email** ***"email"*** - email del creador de los commits en el repositorio local.  

## Asociar repositorio local con repositorio remoto:  
Primeramente, habrá que creer un repositorio remoto en Github, de allí podemos copiar el código que ponemos en la terminal para conectar el repositorio local con el repositorio remoto.  

## Subir documentos al repositorio remoto:  
**git add .** - subir todos los documentos al *staging area*.  
**git add** ***"nombreDocumento"*** -subir documento en concreto al ***staging area***.  
**git commit -m** ***"mensaje"*** - para hacer un 'snapshot' en el repositorio local.  
**git push -u origin main** - para subir los commits al repositorio remoto.  
