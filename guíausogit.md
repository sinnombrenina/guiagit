# Guía básica del uso de git 
### ¿Qué es git?
 *Git* es una herramienta de **control de versiones** que permite a los desarrolladores gestionar y coordinar cambios en el código fuente de proyectos de software.
### ¿Qué es github?
GitHub es una plataforma en línea que permite a los desarrolladores **almacenar, gestionar y colaborar** en proyectos de software utilizando **Git**.
### ¿Qué necesitamos para usar github en nuestros proyectos?
Necesitamos unos requisitos básicos para comenzar en github:
- Darnos de **alta** en la página oficial de github.
- Descargarnos **"Git bash"** para obtener el terminal y poder insertar los comandos.
- Crear una **carpeta** en nuesto **disco local**, no necesariamente debes crear una por cada repositorio, mas sería conveniente para tener todo bien organizado.

### Comandos habituales para trabajar con repositorios remotos 
Seguiremos unos pasos en orden para escribir los comandos correctamente a la hora de crear un repositorio:

**1º.** Iniciaremos con **git init** el cual nos llevará a la rama principla del repositrio en el terminal "`master`".

**2º.** Aplicamos el comando **git remote add origin https://github.com/"nombre de usuario"/"nombre del repositorio".git** este nos comunicará la carpeta del disco con el terminal de github 

**3º.** Con **git status** comprobamos si tenemos ese archivo en la carpeta del disco, en caso de ser así, este saldrá en el terminal en rojo, 
    esto signifi¡ca que el archivo está en la carpeta pero has de guardarlo en el repositorio.

**4º.** **Git add** será nuestro siguiente comando, este nos servirá para subir el/los archivos que tengas en la carpeta del disco ***importante***, 
    puede ejecutarse de dor formas: poniento "." (sube todos los archivos de la carpeta) o "el nombre del arcivo"(sube solo el archivo escrito".

**5º.** Tras haberlo subido debemos añadirlo al repositorio con **git commit -m "Un pequeño comentario que describa el archivo"** pero esto no es el ultimo ya que aun no se habra añadido al repositorio.

**6º.** Aunque pensemos que después de realizar los anteriores 5 pasos ya tendremos el archivo en el repositorio, no es así, aún nos queda un último comando ---> **git push** pero cuidado, 
    la primera que utilices esto te dará un fallo el cual recibras un mensaje con una ampliación del mismo comando, este se coppa y se pega en el terminal, cuando hayas acbado y el terminal no t de ningún mensaje de fallo, por fin habrás conseguido crear un **repositorio**.

 Lee y sigue atentamente los pasos, en caso de dar algún error, vuelva a repasar esta lista y comprobar haberla seguido corretamente.

### Clonar un repositorio

Clonar un repositorio trata de duplicar un repositorio tuyo o de cualquier otro usuario de la página.
Esto lo haremos de la siguiente forma:

**1º-** Elegiremos el repositorio que deseemos clonar, ya bien se nuestro o no, en cuyo caso de que no sea propio tendremos que buscar el nombbre ed usuario de dicha persona.



### ¿Cómo hacer fork de un repositorio existente?
