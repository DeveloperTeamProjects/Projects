# framework-1
*Framework de trabajo para Equipo Dev en H&amp;L Consultores*

## Conceptos clave

- Sprint.
- Kanban.
- Principios.
- Esencia.
- Teoría.
- Valores.
- Historias de Usuario.
- Historia Técnica.
- Épicas.

Criterios para selección de Historias de Usuario desde el Sprint Backlog:
- Valor para el cliente.
- Urgencia.
- Riesgo/oportunidad.
- Esfuerzo.

## H&amp;L Development Team

El H&amp;L Development Team debe estar enfocado  en :
- Trabajar en iteraciones cortas.
- Entregar el producto de forma incremental.
- Eliminar dependencias externas.

H&amp;L Development Team está conformado por:
1. **Master**: Responzable de maximizar el valor del producto, eliminar impedimentos, promover y apoyar al Development Team. 

2. **Development Team**: Profesionales que realizan el trabajo de entregar un incremento de producto "Terminado”. Es un equipo autoorganizado y autogestionado.

## Artefactos

1. **Product Backlog:**
Lista ordenada de todo lo que se identifica y es necesario para el proyecto. Es la unica fuente de requisitos para cualquier cambio que se realice en el producto.

2. **Sprint backlog:**
Subconjunto del Product Backlog y contiene todos los elementos que seran desarrollados durante el Sprint.

## Ceremonias

1. **Sprint Planning:**
- Se selecciona las Historias de Usuario desde el Backlog que se trabajaran en el Sprint actual.
- Tres horas como límite para cada actividad.
- Al finalizar el ciclo del Sprint, se llevarán a cabo dos ceremonias: *Sprint Review* y *Sprint Retrospective*.

2. **Daily Meeting:**

- Reunión inicia cada día, y es parte de ella el development Team como el Master, (el master puede prescindir de ella).
- La ceremonia solo puede ocurrir en la oficina de reuniones o en el espacio de trabajo del development Team (en ausencia del Master solamente).
- La ceremonia comienza a las 9:00 Am con una duración de 15 minutos.
- Cada integrante del development Team debe responder las siguientes preguntas:
   - ¿Que has hecho ayer?
   - ¿Que tienes planificado hacer hoy?
   - ¿Has tenido algún impedimento con las tareas asignadas?

3. **Internal Code Review**

- Ceremonia con fecha de inicio según la planificación planteada estratégicamente por el development Team.
- En ella cada integrante del development Team se encarga de la lectura y posterior retroalimentación del código ejecutado por otro integrante.
- Dos horas como límite para esta actividad.

4. **Code Review**

- Ceremonia un día después de la Internal Code Review.
- Participan en ella el Development Team y el Master.
- Dos horas como límite para esta actividad.
- La ceremonia debe entregar por parte del Master feedbacks referentes a pruebas de funcionalidad, arquitectura y buenas practicas.

5. **Sprint Review**
- Revisar el trabajo que fue completado y no completado.
- Tres horas como límite para esta actividad.

6. **Sprint retrospective**

- Ceremonia tiene lugar inmediatamente después del Sprint Review.
- Una hora como límite para esta actividad.
- Cada integrante del development Team debe responder las siguientes preguntas:
   - ¿Qué cosas se hicieron bien en el Sprint?
   - ¿Que no salió tan bien en el Sprint?
   - ¿Que mejoras vamos a implementar en la próxima iteración?

## Gestión de Sprint
Se utilizará Trello como plataforma oficial en la gestión de Sprint, el cual está conformado por los siguientes tableros:

1. **Sprint Development Board:** Tablero donde se alojan Las Historias de Usuario seleccionadas para el Sprint actual, las cuales se ven afectadas según el avance y la planificación del Development Team. Tiene un flujo horizontal en su desarrollo.

Cada columna tiene las siguientes definiciones:
- *Backlog*: Colección de Historia de Usuario a trabajar dentro del Sprint.
- *Issues*: Historias de Usuario con impedimentos en su ejecución.
- *Doing*: Historias de Usuario en proceso de ejecución.
- *Code Review*: Historia Técnica referente a la ceremonia Code Review.
- *Done*: Historias de Usuario Ejecutadas.
- *Catalog*: Historias de Usuario Catalogadas en cuenta administradora.
- *Deployed*: Despliegue de Historia de Usuario.

2. **Smap PPRDX:** Tablero que representa el producto de valor completo, donde se encuentran las Épicas proyectadas por el Master. 
Las Épicas contienen las Historias de Usuario que se consideraran en el Backlog de cada Sprint.
Tienen un flujo vertical en su avance y cada columna contiene Épicas definidas por el Master.

