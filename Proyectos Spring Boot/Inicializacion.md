# Inicializacion proyecto Spring boot.

### Todos los pasos estan hechos para windows, para otros sistemas la instalacion no debiera ser muy diferente, en muchos casos es seguir los mismos pasos

### Existen dos formas de comenzar un proyecto en spring boot, la primera es con la herramienta spring tool suite que puede ser instalada como complemento en elipse, visual studio code y theia, y la segunda forma es desde una pagina web llamada spring initializr.

### Como paso previo se debe instalar el jdk de java en su version 1.8 o superior.

## instalacion JDK 1.8

1. Existe JDK Oracle (oficial) o Open JDK (open source)

  - JDK Oracle:

    - Ir a https://www.oracle.com/java/technologies/downloads/#java8
    - Elegir version de java (1.8 = 8) respecto al sistema operativo.
    - Al presionar descargar se pedira ingresar con una cuenta o crear una, si no se tiene cuenta presionar en crear cuenta esto es gratuito, seguir los pasos volver al login de la paguina de descarga, iniciar sesion y comenzara la descarga.

  - Open JDK:

    - Ir a https://adoptopenjdk.net/
    - Elegir version de java (1.8 = 8) y descargar.

2. Instalacion
  
  - Ejecutar como administrador el jdk.
  - En el caso de Open jdk en instalacion personalizada en el arbol de "JDK con Hostport" seleccionar todas las opciones (que no quede ninguna con x) esto para evitar problemas de compatibilidad con programar que ejecuten java y que cree la variable de entorno JAVA_HOME, luego si a todo hasta finalizar la instalacion.
  - En el caso de JDK Oracle dar siguiente hasta terminar la instalacion, la configuracion de JAVA_HOME se tiene que hacer manual.
    
    - Configuracion JAVA_HOME
      
      - En el buscador del escritorio ir a "Edit the system environment variables" -> Advanced -> Environment Variables... 
      - En la tabla "System variables" buscar "Path" y presionar editar
      - En la ventana "Edit environment varialbe" presional new y agregar la ruta en el sistema de archivos local donde esta instalado java, la ruta podria ser muy similar a "C:\Program Files\Java\jdk1.8.0_2\bin" -> aceptar
      - Otra opcion es crear no en el Path si no que directamente una nueva variable de entorno, en la tabla "System variables" presionar en new -> en la ventana "New System Variable" en "Variable name" poner JAVA_HOME y en "Variable value" poner el path "C:\Program Files\Java\jdk1.8.0_2\bin" (sin "", puede no ser el mismo buscar en su propio sistema)
  
  - Comprobar la correcta instalacion
    - ir al cmd del sistema, usar el comando "java -version"

    - Si todo salio bien debiera aparecer la version de java instalada

## Crear proyecto con Spring tool suite

1. Ir a la pagina web
  - url: https://spring.io/tools
  - Seleccionar opcion aplicacion basada en eclipse, pluggin visual studio code o aplicacion theia.
  - Con eclipse se presiona descargar luego se descargara un directorio (puede estar comprimido de ser asi descompirmir) y un archivo .jar
  - Dentro del directorio Habra un archivo llamado "SpringToolSuit4.exe", ejecutarlo, comenzara a abrir el programa
  - Al iniciar preguntara donde queremos instalar el ambiente de trabajo (donde se guardaran los proyectos)

2. Crear proyecto

  - En SpringToolSuit se puede crear cualquier tipo de proyecto java pero facilita enormemente la creacion de aplicaciones spring boot
  - ir a File -> New -> Spring Started Proyect
  - Ingregar y seleccionar nombres y versiones y listo ya se tiene inicializado un proyecto spring boot.

## Crear proyecto con spring initializr

1.  Ir a la pagina web https://start.spring.io/

2. Ingrear nombres del proyecto, versiones y dependencias -> presionar "GENERATE".

3. Se creara el proyecto y se descargara.

4. ir al editor de codigo de preferencia, en mi caso Spring tool suite -> File -> import -> Maven -> Existing Maven Proyect -> Buscar proyecto descargado y seleccionar -> Finish -> isto ya se tiene inicializado un proyecto spring boot.