# FASE DE DISEÑO

- [FASE DE DESEÑO](#fase-de-diseño)
  - [1- Diagrama da arquitectura](#1--diagrama-de-la-arquitectura)
  - [2- Casos de uso](#2--casos-de-uso)
  - [3- Diagrama de Base de Datos](#3--diagrama-de-base-de-datos)
  - [4- Deseño de interface de usuarios](#4--diseño-de-interfaz-de-usuarios)

> *EXPLICACIÓN:* Este documento inclúe os diferentes diagramas, esquemas e deseños que axuden a describir mellor o [nome do proxecto] detallando os seus compoñentes, funcionalidades, bases de datos e interface.

## 1- Diagrama de la arquitectura

> *EXPLICACIÓN:* Incluír os diagramas de arquitectura que representen de forma gráfica a aplicación, os seus compoñentes e a súa interrelación: front-end, back-end, bases de datos, nube, microservizos, etc.

La arquitectura de este proyecto sería algo así:

![Diagrama de arquitectura](../img/DiagramaGeneral.png)

En este caso especifícamente con estas tecnologías:
![Diagrama de arquitectura](../img/DiagramaEspecifico.png)

## 2- Casos de uso

El usuario podrá registrarse, iniciar sesión, jugar y guardar sus puntuaciones, editar usuario y realizar pagos.

![Diagrama de casos de uso](../img/Diagrama-de-caso-de-uso-OneTap.jpeg)

## 3- Diagrama de Base de Datos

El diseño de la base de datos consta de tres tablas: "games", "users" y "scores". 

La tabla "games" almacena información sobre los juegos, incluyendo un identificador único, nombre, descripción y fecha de estreno.

La tabla "users" almacena información de los usuarios, incluyendo un identificador único, nombre, correo electrónico y contraseña.

La tabla "scores" almacena los puntajes de los usuarios en los juegos, con claves foráneas que hacen referencia a los identificadores de los juegos y usuarios correspondientes. Además, se registra la fecha del último puntaje obtenido.

Las relaciones entre las tablas son las siguientes:
- La tabla "scores" tiene una clave foránea "game_id" que referencia al identificador de un juego en la tabla "games".
- La tabla "scores" también tiene una clave foránea "user_id" que referencia al identificador de un usuario en la tabla "users".

Estas relaciones permiten asociar los puntajes de los usuarios con los juegos y usuarios correspondientes.

![Diagrama de Base de Datos](../img/ModeloRelacionalBBDD_OneTap.png)


## 4- Diseño de interfaz de usuarios

> *EXPLICACIÓN:* Neste apartado deben incluírse unha mostra representativan dos mockups da aplicación. Estes mockups deben incluír todas as vistas da aplicación, é dicir, todas as páxinas diferentes que unha persoa usuaria (de calquera tipo) vai poder ver. Tamén se debe incluír información de como navegar dunha ventá a outra.
>
> Os mockups axudan no deseño da aplicación. Poden facerse á man, cunha aplicación ou a través dunha web do estilo: diagrams Un mockup permite ver como se verá unha páxina concreta dunha aplicación web. O deseño de mockups axuda a:
>
> - Avanzar moi rápido na parte frontend: ao ter os mockups realizados, permite saber que elementos vai ter cada vista e onde colocalos.
> - Visualizar a información que vai a ser necesaria mostrar. Sabendo con que información imos traballar e sabendo a información que necesitamos mostrar, podemos organizar os datos dunha forma axeitada para gardalos na base de datos.
>
> Se temos as ideas máis claras do noso proxecto podemos sustituir os mockups por prototipos.