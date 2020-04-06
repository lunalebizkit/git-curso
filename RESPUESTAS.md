#Respuestas 

1. **¿Qué es git?**
Git es un sistma de control de versiones, controla o administra las distintas versiones de un programa
2. **¿Por qué queremos utilizar git?**
Porque necesitamos llevar un listado con los cambios que hacemos en los codigos del programa, ademas para poder compartir con otros desarrolladores nuestros programas y cooperar con los demas desarrolladores y programas, teniendo la seguridad de no perder la informacion ya que éste puede revertir los cambios hechos. 
3. **¿Qué es el bash que instala git?**
Es una consola o terminal con mejores funcionalidades porque trae los mejores conceptos de UNIX
4. **Describa los estados (working directory, staging area, repository**
#####Working Directory
Este estado **working directory** indica que estamos trabajando sobre el directorio, o sea, donde tenemos guardado el proyecto y archivos en nuestra computadora.
#####Staging Area
En este estado es donde vamos a agregar nuestros archivos una vez que los terminamos de preparar o queremos que sea parte de "git" y asi sera parte de nuestra área de trabajo.
#####Repository
En este estado se podria decir que es cuando subimos nuestro proyecto a la nube o a un servidor para guardarlo de manera online, donde puede ser compartido, intervenido o simplemente guardado en el servidor. 

5. **Describa el flujo para crear un nuevo repositorio git**
   * Una vez ubicado sobra el directorio donde vamos a guardar nuesto proyecto o programa, tecleamos **git init** y enter
   * posteriormente GIT creara un repositorio o deposito en la carpeta del proyecto o mejor dicho creará una carpeta llamada **.git**
6. **Describa el flujo para agregar un archivo simple al repositorio**
   * Utilizamos el comando **git status** mas enter y nos mostrará los archivos que contiene la carpeta del proyecto
   * Luego tecleamos **git add** y el nombre de los archivos que deseamos agregar al Staging Area o area de trabajo
   * De esta manera los archivos que hemos agregado seran parte del proyecto y podremos modificarlos o trabajar en git.
7. **Describa el flujo para cambiar el archivo agregado y guardar los cambios en el repositorio**
   * Una vez modificado el archivo en un editor de codigo tecleamos **git status** y enter para ver el estado de los archivos
   * en el caso que haya un archivo modificado tecleamos **git add** y enter para agrergarlo al area de trabajo nuevamente
   * Luego escribimos el comando **git commit** y enter, asi se creara un punto de control de nuestro codigo (hay que tener en cuenta de configurar datos del usuario)
8. **¿Cómo hago para ignorar un archivo o carpeta?**
Para ignorar un archivo o carpeta, en el programa se crea un archivo "*.ignore*". Dentro de este archivo se nombrarán los archivos o carpetas que desean ser ignorados por git
9. **Explique que es un branch. Dé un pequeño ejemplo de cómo haria uno**
Branch es una opcion que da el programa GIT para poder cambiar de rama o versiones alternativas del proyecto en el cuál estamos trabajando.
 * Creamos un proyecto o programa bajo la rama "master".
 *  Luego creamos un usuario o rama utilizando **git+branch+espacio+nombre de la version alternativa "Usuario1"**
 *   despues tecleamos **git checkout+espacio+Usuario1**. Ahora podemos trabajar sobre el mismo proyecto sin perder la base del usuario o rama original.
10. **¿Qué es el "git add"?**
Es un comando que te permite agregar un archivo del proyecto que se encuentra en el directorio o ubicacion, al area de trabajo o entorno de trabajo **(Staging Area)**, al agregarlo se guarda con los ultimos cambios. 
11. **¿Cómo cambiamos de un branch a otro?**
 * Tecleamos **git branch** para que nos muestre los usuarios o ramas disponibles. 
 * Luego tecleamos **git checkout** (y el usuario al que queremos cambiar) entonces en la barra de direccion o directorio mostrará al final de la direccion entre parentesis el nombre del usuario.

Ej: c:\usuarios\alumno\escritorio\Proyecto **(Master)**