# Proyecto fin de ciclo

- [Proyecto fin de ciclo](#proyecto-fin-de-ciclo)
  - [Tablero del proyecto](#tablero-del-proyecto)
  - [Descripción](#descripción)
  - [Instalación / Puesta en marcha](#instalación--puesta-en-marcha)
  - [Uso](#uso)
  - [Sobre el autor](#sobre-el-autor)
  - [Licencia](#licencia)
  - [Índice](#índice)
  - [Guía de contribución](#guía-de-contribución)
  - [Enlaces](#enlaces)

## Tablero del proyecto

| Estado del Proyecto | Descripción |
| --- | --- |
| Funcional | El proyecto está funcionando, pero abierto a nuevas mejoras e implementaciones. |

## Descripción

Este proyecto es una página web de minijuegos, un lugar donde los jugadores pueden disfrutar de varios juegos y competir por las máximas puntuaciones. Los usuarios pueden registrarse para guardar sus puntuaciones y seguir su progreso. La idea es crear una comunidad de jugadores que disfruten de los juegos y quieran mejorar sus habilidades y ser recompensados por ser los mejores. La página web será diseñada para ser intuitiva y fácil de usar, para que cualquier persona, independientemente de su conocimiento técnico, pueda jugar y divertirse. Las tecnologías utilizadas para el desarrollo de este proyecto incluirán HTML, CSS, JavaScript, PHP (framework CakePHP) y un servidor backend para gestionar los datos de los usuarios y las puntuaciones.

## Instalación / Puesta en marcha

Para poner en marcha la aplicación, necesitarás tener instalado Docker y Docker Compose en tu sistema. Una vez instalados, sigue los siguientes pasos:

1. Clona el repositorio del proyecto en tu sistema local usando Git.
2. Navega hasta el directorio del proyecto.
3. Ejecuta el comando `docker-compose up` en el terminal. Este comando construirá e iniciará los contenedores necesarios para la aplicación.

Los contenedores que se crearán son los siguientes:

- Un contenedor para la base de datos, que utilizará una imagen de MySQL.
- Un contenedor para el servidor web, que utilizará una imagen de Apache.
- Un contenedor para adminer, que utilizará una imagen de adminer.

Estos contenedores se comunicarán entre sí para proporcionar un entorno de desarrollo completo para la aplicación.

Una vez que los contenedores estén en marcha, puedes acceder a la aplicación web navegando a `http://localhost` en tu navegador.

O si quieres acceder directamente a la página en funcionamiento, sin configurar localmente la página: `onetap.ddns.net`

## Uso

Para utilizar la aplicación, los usuarios deben navegar hasta la página principal donde verán una lista de juegos disponibles. Pueden elegir un juego para jugar y, una vez que el juego se carga, podrán jugarlo. Si el usuario está registrado e inició sesión, sus puntuaciones serán guardadas y podrán ver sus puntuaciones máximas en cada juego. También podrán ver una tabla de clasificación global (aparecerán los 3 mejores de cada juego) para cada juego, donde podrán competir con las puntuaciones máximas de otros usuarios. Si el usuario no está registrado o no ha iniciado sesión, aún podrán jugar a los juegos, pero sus puntuaciones no serán guardadas.

## Sobre el autor

Sobre mí, soy un desarrollador web apasionado con fuertes habilidades en JavaScript y PHP. Tengo una gran experiencia en desarrollo frontend y backend, creando soluciones eficientes y escalables. Mi motivación para este proyecto viene de mi pasión por los juegos y la programación. Quiero crear un espacio donde los jugadores puedan competir y divertirse, al mismo tiempo que mejoran sus habilidades y que sean recompensados por su esfuerzo. Creo que este proyecto puede llenar un nicho de mercado para juegos web competitivos y accesibles. Durante el proceso de creación de este proyecto, puedes contactarme a través de mi correo electrónico (eloypro12@gmail.com) o a través del sistema de mensajes de GitHub.

## Licencia

Este proyecto está licenciado bajo la licencia Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0). Esto significa que puedes compartir y adaptar el material para cualquier propósito, siempre y cuando:

- Des crédito, proporcionando un enlace a la licencia, e indicando si realizaste cambios. Puedes hacerlo de cualquier manera razonable, pero no de una manera que sugiera que el licenciante te respalda a ti o a tu uso.
- No lo utilices con fines comerciales.
- Si remezclas, transformas o construyes a partir del material, debes distribuir tus contribuciones bajo la misma licencia que el original.

Para más información, consulta la [página de la licencia CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.es).

## Índice

1. [Anteproyecto](doc/templates/1_Anteproyecto.md)
2. [Análisis](doc/templates/2_Analisis.md)
3. [Diseño](doc/templates/3_Diseño.md)
4. [Codificación y pruebas](doc/templates/4_Codificacion_y_pruebas.md)
5. [Implantación](doc/templates/5_Implantacion.md)
6. [Referencias](doc/templates/6_Referencias.md)
7. [Incidencias](doc/templates/7_Incidencias.md)

## Guía de contribución

Si estás interesado en contribuir a este proyecto de software libre, ¡te damos la bienvenida! Aquí hay algunas formas en las que puedes contribuir:

1. **Desarrollo de nuevas funcionalidades**: Si tienes ideas para mejorar el proyecto, puedes implementar nuevas funcionalidades y enviar una solicitud de extracción (pull request) para que sean revisadas y consideradas.

2. **Corrección y optimización del código**: Si encuentras errores o áreas de mejora en el código existente, puedes enviar correcciones y optimizaciones para ayudar a mantener el proyecto en buen estado.

3. **Realización de pruebas automatizadas**: Las pruebas automatizadas son fundamentales para garantizar la calidad del software. Si tienes experiencia en pruebas unitarias, de integración o de rendimiento, puedes contribuir agregando pruebas automatizadas al proyecto.

4. **Desarrollo de plugins o interfaces de integración**: Si tienes conocimientos en desarrollo de plugins o integración con otras herramientas o servicios, puedes desarrollar nuevas interfaces de integración que mejoren la funcionalidad del proyecto.

Recuerda seguir las mejores prácticas de desarrollo, documentar tus cambios y asegurarte de que tus contribuciones sean coherentes con la visión y los objetivos del proyecto.

¡Gracias por tu interés en contribuir al proyecto! Esperamos recibir tus aportes.

## Enlaces

- [Documentación de cakephp](https://cakephp.org/)
- [Documentación de JavaScript](https://developer.mozilla.org/es/docs/Web/JavaScript)
- [Documentación de PHP](https://www.php.net/manual/es/index.php)
- [Documentación de HTML](https://developer.mozilla.org/es/docs/Web/HTML)
- [Documentación de CSS](https://developer.mozilla.org/es/docs/Web/CSS)
