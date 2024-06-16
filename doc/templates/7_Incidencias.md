# INCIDENCIAS E TAREFAS
- [INCIDENCIAS E TAREFAS](#incidencias-e-tarefas)
  - [1- Incidencias](#1--incidencias)
  - [2- Tarefas](#2--tarefas)

## 1- Incidencias

Aquí se documenta todo tipo de incidencias durante la creación del proyecto:

Durante la creación del juego se hizo una primera versión de prueba en la que fallaban ciertos recursos, y se englobaba todo el juego en un único archivo. Esto se modificó de manera que se ejecuta primero un motor que hace la carga de todo el juego (engine.js) y despues cada juego tendrá su propio comportamiento, reglas (juego.js y index.html), recursos etc.
Hubo errores de cargas de recursos, animaciones mal hechas o sonidos o música extremadamente alta, pero se han solicionado.
También se ha corregido la fluidez del juego, que ahora se optimiza a la velocidad de respuesta del monitor.

Se ha intentado crear mas juegos pero por el limitado tiempo se ha dejado a medias un juego que no se puede presentar ya que no está en funcionamiento.

Durante la carga de la página ha habido mucho aprendizaje con el framework de cakephp ya que ha habido ciertos fallos de enrutamiento y demás que han sido solucionados posteriormente.

La página web se ha intentado iniciar con docker pero debido a diferentes incidencias con el docker desktop se descartó y se empezó con XAMPP. Debido a un problema de electricidad durante la fase final de desarrollo el XAMPP se corrompió y tras no encontrar solución al problema se volvió a intentar a ejecutar la app web a través de contenedores con docker, que esta vez si ha sido exitosa.

## 2- Tarefas

Aquí se documenta todas las tareas realizadas durante la creación del proyecto:

 - La creación de un juego en JavaScript.
 - Creación de la página (index).
 - Creación de la base de datos.
 - Registro de usuarios.
 - Iniciar sesión.
 - Salir de la sesión.
 - Listado de juegos con filtro incluido (peticiones AJAX).
 - Visualización del juego con opción a pantalla completa.
 - Guardado de puntuaciones de los usuarios.
 - Listado de puntuaciones de los usuarios.
 - Edición de usuarios.
 - Generar imagenes para los juegos y cards de la página.