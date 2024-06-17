# FASE DE CODIFICACIÓN E PROBAS

- [FASE DE CODIFICACIÓN E PROBAS](#fase-de-codificación-e-probas)
  - [1- Codificación](#1--codificación)
  - [2- Prototipos](#2--prototipos)
  - [3- Innovación](#3--innovación)
  - [4- Pruebas](#4--pruebas)

> Este documento explica como se debe realizar a fase de codificación e probas.

## 1- Codificación

> Crea unha carpeta no teu repositorio e sube o código frecuentemente.
>
> Mentres se vai codificando a aplicación, iranse atopando problemas e haberá que ir modificando aspectos do deseño. Estes cambios tamén se deben recoller na documentación.

El proyecto se encuentra comprimido en un archivo .zip en la carpeta "src/" del proyecto.

## La creación de un juego en JavaScript

Para crear un juego en JavaScript, se seguieron los siguientes pasos:

1. Diseño de la mecánica del juego y definición los objetivos y reglas del mismo.
2. Creación de los elementos gráficos necesarios, como sprites, fondos y efectos visuales.
3. Implementación la lógica del juego utilizando JavaScript.
4. Gestión de la interacción del usuario con el juego, como eventos de teclado o clics del ratón.
5. Añadido de efectos de sonido y música para mejorar la experiencia del jugador.
6. Realización de pruebas exhaustivas para asegurarte de que el juego funciona correctamente y es divertido de jugar.

## Creación de la página (index)

Para crear la página principal (index) de la aplicación, se siguieron estos pasos:

1. Creación de un controllador llamado "index".
2. Define la estructura básica del documento, con default.php y index.php.
3. En el `<head>`, añadidas las etiquetas `<title>` para el título de la página y `<link>` para enlazar los estilos CSS (cakephp).
4. En el `<body>`, añadidos los elementos necesarios para mostrar la información principal de la aplicación, como encabezados, imágenes y texto descriptivo.
5. Utilizada plantilla CSS para dar estilo a la página y mejorar su apariencia visual.
6. Añade enlaces a otras páginas de tu aplicación, como el registro de usuarios o el listado de juegos.

## Creación de la base de datos

Para crear la base de datos de la aplicación, se siguieron estos pasos:

1. Se decidió qué sistema de gestión de bases de datos (SGBD) utilizar, MySQL, y se gestionará con adminer.
2. Instala el SGBD en el servidor o máquina local (XAMPP o contenedores docker).
3. Creación de una nueva base de datos utilizando el cliente del SGBD o una herramienta de administración como adminer.
4. Definición de las tablas necesarias para almacenar la información de tu aplicación, como usuarios, juegos y puntuaciones.
5. Definición de las relaciones entre las tablas utilizando claves primarias y claves foráneas.
6. Añadido de los campos necesarios en cada tabla para almacenar la información relevante, como nombres de usuario, contraseñas, puntuaciones...

## Registro de usuarios

Para implementar el registro de usuarios en la aplicación, se siguieron estos pasos:

1. Crea un formulario de registro en tu página de registro (por ejemplo, "register.php").
2. Añadido de los campos necesarios para que los usuarios introduzcan su nombre de usuario, contraseña...
3. Utilizado CakePHP para validar los datos introducidos por el usuario y mostrar mensajes de error si es necesario.
4. En el lado del servidor, implementado un controlador o script que reciba los datos del formulario y los procese.
5. Verifica que la contraseña sea correcta (confirmar contraseña).
6. Si los datos son válidos, crea un nuevo registro en la tabla de usuarios con la información proporcionada por el usuario.

## Iniciar sesión

Para implementar la funcionalidad de inicio de sesión en la aplicación, se siguieron estos pasos:

1. Creado un formulario de inicio de sesión en tu página de inicio de sesión con una ventana modal y JavaScript.
2. Añade los campos necesarios para que los usuarios introduzcan su correo y contraseña.
3. Utilizado CakePHP para validar los datos introducidos por el usuario y mostrar mensajes de error si es necesario.
4. En el lado del servidor, implementado un controlador o script que reciba los datos del formulario y los procese.
5. Verifica que el nombre de usuario y la contraseña coincidan con los registros almacenados en la base de datos.
6. Si los datos son válidos, crea una sesión para el usuario y redirígelo a la página principal de la aplicación.

## Salir de la sesión

Para implementar la funcionalidad de cierre de sesión en la aplicación, se siguieron estos pasos:

1. Añade un enlace o botón en la página principal o en la barra de navegación para que los usuarios puedan cerrar sesión.
2. En el lado del servidor, implementado un controlador o script que destruya la sesión del usuario.
3. Redirige al usuario a la página principal.

## Listado de juegos con filtro incluido (peticiones AJAX)

Para implementar el listado de juegos con filtro incluido utilizando peticiones AJAX, se siguieron estos pasos:

1. Creación de una página o sección en la aplicación donde se mostrará el listado de juegos.
2. Utilizado JavaScript para realizar una petición AJAX al servidor para obtener los datos de los juegos.
3. En el lado del servidor, implementado un controlador o script que reciba la petición AJAX y devuelva los datos de los juegos filtrados según los parámetros proporcionados.
4. Utiliza JavaScript para procesar los datos recibidos y mostrarlos en la página de forma dinámica.
5. Añadido un elemento de filtrado en la página, como campo de búsqueda, y utilizado JavaScript para enviar nuevas peticiones AJAX al servidor cuando se realicen cambios en el filtro.
6. Actualización de la lista de juegos en la página con los resultados de las nuevas peticiones AJAX.

## Visualización del juego con opción a pantalla completa

Para permitir la implementación del juego, se siguieron estos pasos:

1. Creado un iframe donde se se cargará el juego en un html.
2. Creados los bordes del juego y tamaño de la ventana para que no sobre salga o se quede en un tamaño incómodo.

Para permitir la visualización del juego con opción a pantalla completa, se siguieron estos pasos:

1. Añade un botón o enlace en la página de detalles del juego o en la lista de juegos para permitir al usuario abrir el juego en pantalla completa.
2. Utilizado JavaScript para detectar cuando el usuario hace clic en el botón o enlace.
3. Utilizado JavaScript para solicitar al navegador que muestre el juego en pantalla completa.

## Guardado de puntuaciones de los usuarios

Para guardar las puntuaciones de los usuarios en la aplicación, se siguieron estos pasos:

1. Creada una tabla en la base de datos para almacenar las puntuaciones de los usuarios, con campos como el ID del usuario, el ID del juego, la puntuación obtenida y la fecha del momento que se obtuvo la puntuación.
2. En el lado del servidor, implementado un controlador o script que reciba la puntuación del usuario y la guarde en la base de datos.
3. Verifica que el usuario esté autenticado antes de guardar la puntuación.
4. Si el usuario ya tiene una puntuación registrada para el juego, actualiza el registro existente con la nueva puntuación.
5. Si el usuario no tiene una puntuación registrada para el juego, crea un nuevo registro en la tabla de puntuaciones.

## Listado de puntuaciones de los usuarios

Para mostrar los 3 mejores puntajes de cada juego en la aplicación, se siguieron estos pasos:

1. Creada una página o sección en la aplicación donde se mostrarán los puntajes.
2. En el lado del servidor, se implementó un controlador o script que obtenga los datos de los puntajes de los usuarios desde la base de datos y filtra los 3 mejores de cada juego.
3. Utiliza JavaScript para procesar los datos recibidos y mostrar los 3 mejores puntajes de cada juego en la página de forma dinámica.
4. Muestra el nombre del juego, el nombre del jugador, el puntaje y la fecha del puntaje para cada uno de los 3 mejores puntajes de cada juego.
5. Actualiza la lista de puntajes en la página cuando se agreguen nuevos puntajes o se modifiquen los existentes.

## Edición de usuarios

Para permitir la edición de usuarios en la aplicación, se siguieron estos pasos:

1. Creada una página o sección en tu aplicación donde los usuarios puedan editar su información.
2. En el lado del servidor, implementa un controlador o script que reciba los datos actualizados del usuario y los guarde en la base de datos.
3. Verifica que el usuario esté autenticado antes de permitir la edición de su información.
4. Rellenados los campos del formulario con la información actual del usuario para que pueda realizar cambios.
5. Actualización de la información del usuario en la base de datos cuando se envíe el formulario de edición.

## Generar imágenes para los juegos y cards de la página

Para generar imágenes para los juegos y cards de la página, se siguieron estos pasos:

1. Creación o seleccionado de imágenes relevantes creadas por ia para cada juego y para las cards de la página.
2. Utilizadas herramientas de edición de imágenes como Photoshop o GIMP para ajustar el tamaño y la resolución de las imágenes según las necesidades.
3. Guardadas las imágenes en un formato adecuado, como JPEG o PNG.
4. Utilizadas las imágenes en la aplicación, ya sea en la página principal, en la lista de juegos o en las páginas de detalles de los juegos, según corresponda.
5. Asegúrarse de que las imágenes se carguen correctamente y se muestren de forma adecuada en todos los dispositivos y navegadores compatibles.



## 2- Prototipos

El prototipo se encuentra en: src/Prototipo.fig

[Prototipo](../../src/Prototipo.fig)

## 3- Innovación

En este proyecto, hemos decidido utilizar CakePHP como framework de desarrollo. CakePHP es una opción ideal para nuestra plataforma de videojuegos por varias razones:

1. **Rápido desarrollo**: CakePHP sigue el principio de "convención sobre configuración", lo que significa que proporciona una estructura y convenciones predefinidas que aceleran el proceso de desarrollo. Esto nos permite enfocarnos en la lógica de negocio y funcionalidades específicas de nuestra plataforma de videojuegos, en lugar de perder tiempo en configuraciones tediosas.

2. **MVC robusto**: CakePHP sigue el patrón de diseño Modelo-Vista-Controlador (MVC), lo que nos permite separar claramente la lógica de negocio, la presentación y la interacción con la base de datos. Esto facilita el mantenimiento y la escalabilidad de nuestra plataforma, ya que los componentes están bien organizados y acoplados de manera eficiente.

3. **Seguridad integrada**: CakePHP cuenta con medidas de seguridad integradas, como la protección contra ataques de inyección SQL, ataques de cross-site scripting (XSS) y protección contra falsificación de solicitudes entre sitios (CSRF). Esto nos brinda una capa adicional de seguridad para proteger los datos y la integridad de nuestra plataforma de videojuegos.

4. **Amplia comunidad y documentación**: CakePHP cuenta con una comunidad activa de desarrolladores y una amplia documentación. Esto significa que podemos encontrar fácilmente soluciones a problemas comunes, acceder a plugins y extensiones desarrollados por la comunidad, y recibir soporte en caso de que surjan dudas o dificultades durante el desarrollo de nuestra plataforma.

En resumen, CakePHP es una elección sólida para nuestra plataforma de videojuegos debido a su rápido desarrollo, su arquitectura MVC robusta, su seguridad integrada y el respaldo de una comunidad activa. Con CakePHP, podemos construir una plataforma de videojuegos eficiente y segura, brindando una experiencia de usuario excepcional a nuestros jugadores.


## 4- Pruebas

Deben describirse las pruebas realizadas y las conclusiones obtenidas. Describir los problemas encontrados y cómo fueron solucionados.

En la primera versión de prueba, hubo problemas con algunos recursos y todo el juego estaba contenido en un solo archivo. Sin embargo, se realizaron modificaciones para mejorar esto. Ahora, el juego se ejecuta utilizando un motor que carga todos los recursos necesarios (engine.js), y luego cada juego tiene su propio comportamiento, reglas y recursos específicos (juego.js e index.html).

Durante el desarrollo, se encontraron errores relacionados con la carga de recursos, animaciones incorrectas y problemas con el volumen de sonidos y música. Afortunadamente, todos estos problemas fueron solucionados.

Además, se mejoró la fluidez del juego para que se ajuste a la velocidad de respuesta del monitor, lo que proporciona una experiencia de juego más suave.

Se intentó crear más juegos, pero debido a limitaciones de tiempo, uno de los juegos quedó incompleto y no se pudo presentar, ya que no funcionaba correctamente.

Durante la carga de la página web, también se enfrentaron desafíos relacionados con el framework de CakePHP, como problemas de enrutamiento, que se resolvieron posteriormente.

Inicialmente, se intentó iniciar la página web utilizando Docker, pero debido a problemas con Docker Desktop, se descartó esa opción y se optó por utilizar XAMPP. Sin embargo, durante la fase final de desarrollo, hubo un problema de electricidad que corrompió la instalación de XAMPP. Después de no encontrar una solución, se decidió volver a intentar ejecutar la aplicación web utilizando contenedores con Docker, y esta vez fue exitoso.

