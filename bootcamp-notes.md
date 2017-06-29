# NOTAS DE CLASE

### Configuración del entorno de desarrollo
Para ajustar el entorno de desarrollo se realizan los siguientes pasos:

1. Instalar Git y Git Bash.
    Git es un sistema de control de versiones descentralizado, permite controlar las distintas versiones del código fuente.
    La descarga para la instalación se hace directamente desde de la página: [Git](https://git-scm.com/)
1. Configurar la clave SSH.
    La clave SSH proporciona una forma más segura de iniciar sesión en un servidor privado virtual.
    para crear una, es necesario asegurarse de no tener ya una clave verificando en la terminal con los siguientes comandos: 
    -cd ~/.ssh  (Preguntarle al profe)
    -ls
    Aquí se muestra si en la carpeta .ssh está o no la llave de seguridad, si no existe ningun archivo en la carpeta se ejecutan los siguientes comandos:
    -$ ssh-keygen
A continuación se solicita la ubicación donde se va a guardar la clave y una contraseña la cual se puede dejar en blanco para no teclearla siempre que se utilice.  
1. Crear una cuenta en GitHub.
    GitHub es una plataforma de desarrollo colaborativo para almacenar proyectos utilizando el sistema de control de versiones Git
Para crear una cuenta solo es necesario seguir los pasos que se muestran en la página: [GitHub](https://github.com/)
1. Configurar la clave pública SSH en GitHub.
1. Instalar editor de texto.
1. Instalar Node.js
Node.js es un interprete de JavaScript de lado del servidor está diseñado para construir aplicaciones en red escalables, escritas en código que puede manejar varias conexiones simultaneas en un solo dispositivo. 
Para descargar e instalar se ingresa en la página de [Node.js](https://nodejs.org/es/download/).
  
  ### WebTask
es una forma sencilla de ejecutar código de frontend que elimina o reduce la necesidad de un backend. 
Para usar WebTask se recomienda que sea atravez de la interfaz wt en la linea de comandos (Terminal) los siguientes comandos son los necesarios para crear y editar:
-wt create --> Crea un editor en la nube
-wt edit --> Carga la página donde está el editor en la web.
  
  ### MarckDown
es un lenguaje de marcado rápido que facilita la publicación tanto en la forma de entrada como de salida, inspirdo en algunas convenciones existentes para marcar mensajes de correo electrónico usando texto plano. En el cual está basado este texto.

Existe un editor on line llamado [Dillinger](http://dillinger.io/) en el cual se puede escribir con este lenguaje, también es posible instalar este paquete en editores de texto como [Sublime](https://www.sublimetext.com/3) para realizar textos de sintaxis básica. Para esto, en el caso de [Sublime](https://www.sublimetext.com/3), es necesario descargar el paquete de control siguiedo las siguientes instrucciones de instalación: https://packagecontrol.io/installation.

  ### Uso de la terminal
  
   - Comandos de direcciones básicas:
  
      | Comando | Documentation |
      |-----------|---------------|
      | ls | Lista de contenidos del directorio actual.|
      | ls -l | Lista de contenidos del directorio actual en formato largo.|
      | ls -a | Lista de contenidos del directorio actual incluyendo archivos ocultos.|
      |-----------|---------------| (Preguntar al profe)
      | cd: | Cambia la dirección a home |
      | cd dir | Cambia a la dirección "dir". |
      | cd ... | Regresa a la dirección anterior.|
      |-----------|---------------|
      | mkdir dir | Crea una dirección en dir.|
      | rm -r dir| Elimina dir de la dirección actual.|
      | rm -rf dir | Elimina dir de la dirección actual (Forzado).|
      |-----------|---------------|
      | cp -r dir1 dir2 | Copia dir1 a dir2. |
      | cd - | Cambia el directorio previo de la dirección. |

   - Comandos de archivos básicas:
  
      | Comando | Documentation |
      |-----------|---------------|
      | rm file | Remueve el archivo "file".|
      | rm -f file | Remueve el archivo "file" (Forzado).|
      | cp file1 file2 | Copia file1 a file2.|
      |-----------|---------------| (Preguntar al profe)
      | cd: | Cambia la dirección a home |
      | cd dir | Cambia a la dirección "dir". |
      | cd ... | Regresa a la dirección anterior.|
      |-----------|---------------|
      | mv file1 file2 | Renombra o mueve file1 a file2.|
      | touch file | Crea o recarga file.|
      | more file | Salida de archivo de file con Scroll a diferencia de cat.|