# Inicializacion proyecto vue js.

## Existen 2 versiones de vue usadas actualmente, vue 2 y vue 3, en este documento se generalizaran ambas.

### Instalacion:

1. instalar nodejs

2. instalar CLI

- npm install -g @vue/cli
  
   - El flag -g dice que se instalara de manera global en la maquina.
   - Comprobar que se ha instalado bien con el comando 'vue --version'

3. actualizar CLI

- npm update -g @vue/cli

4. crear proyecto vuejs

- vue create 'PROJECT-NAME'
    - Si es primera vez que se crea un proyecto vue aparecera algo similar a esto:
      - Default ([Vue 3] babel, eslint)
      - Default ([Vue 2] babel, eslint)
      - Manually select features
    - La primera opcion crea un pruecto vuejs 3 standart
    - La segunda opcion crea un pruecto vuejs 2 standart
    - Babel es un framework para compatibilizar tecnologias de antiguos navegadores con las nuevas.
    - eslint son reglas para estandarizar el codigo.
    - La tercera opcion permite agregar mas capacidades, si se selecciona apareceran las siguientes opciones:
      - Presiona (space) para seleccionar, (a) selecciona todas, (i) deselecciona y (enter) para procesar lo seleccionado.
      - (*) Babel
      - () TypeScript
      - Progressive Web App (PWA) Support
      - () Router
      - Vuex
      - CSS Pre-processors
      - Linter / Formatter
      - Unit Testing
      - E2E Testing
    - De todas la opciones antiores las mas importantes son:
      - Babel: Compatibilidad js legacy/moderno
      - Router: Capacidad de enrutar path dentro del proyecto
      - Vuex: Capacidad de almacenamiento de variables y funciones de maner global en la aplicacion.
      - Linter: estandarizacion para tener codigo limpio.
      - Unit Testing: test unitarios
  - Al precionar (enter) la siguiente vista permite seleccionar la version de vuejs
    - 3.x
    - 2.x
    
    La desicion de cual tomar estara estrechamente ligada a los requerimientos y constumbres del desarrollador, vue 3 es mas ligero y cuenta con una api compose, pero en escencia todo lo que puede hacer vue 3 lo puede hacer vue 2, hay algunas librerias que aun no son compatibles con vue 3.
  - Luego de seleccionar version aparecera algo asi:
    - use history mode for router (requires proper server setup for index fallback in production) Y/N
    - Esto pregunta si la aplicacion tendra modo historia, este modo es util para que las url tengan el formato estandar y se puede retroceder a paginas anteriores sin problemas (se debe de igual forma hacer una configuracion a nivel de servidor web debido a que vue trabaja en formato una pagina)
    - Para mayor detalle visitar la siguiente pagina web https://router.vuejs.org/guide/essentials/history-mode.html
  - Al presionar (enter) la siguiente vista permite agregar diferentes configuraciones de ESLint, seleccionar el de preferencia.
  -  Al presionar (enter) permite agregar configuraciones adicionales de ESLint
  - Al presionar (enter) la siguiente vista permite seleccionar el framework para unit test
    - Jest
    - Mocha + Chai
  - Seleccionar el de preferencia.
  -  Al presionar (enter) permite seleccionar si guardar configuraciones en archivo conf o en json, seleccionar el de preferencia.
  - Al presionar (enter) comenzara a crearse el proyecto

5. Testear correcta instalacion
  - En la consola usar comando: cd 'PROJECT-NAME'
  - npm run serve
  - Si todo a resultado correcto se vera en consola algo como lo siguiente
    - App running at: 
      - Local: http://localhost:8080/
      - Network: http://192.168.1.84:8080/
    - Para ver la pagina por defecto ir a la ruta 'Local', desde visual studio code presionando 'ctrl + enter'