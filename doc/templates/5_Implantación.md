# FASE DE IMPLANTACIÓN

- [FASE DE IMPLANTACIÓN](#fase-de-implantación)
  - [1- Manual técnico](#1--manual-técnico)
    - [1.1- Instalación](#11--instalación)
    - [1.2- Administración do sistema](#12--administración-del-sistema)
  - [2- Manual de usuario](#2--manual-de-usuario)
  - [3- Mejoras futuras](#3--mejoras-futuras)

## 1- Manual técnico

### 1.1- Instalación

Para descargar el código del proyecto y continuar su desarrollo, sigue estos pasos:

1. Asegúrate de tener Docker Compose instalado en tu sistema. Puedes encontrar instrucciones de instalación en la documentación oficial de Docker.

2. Abre tu IDE preferido, como Visual Studio Code, y navega hasta el directorio del proyecto.

3. Ejecuta el siguiente comando en la terminal para construir y levantar los contenedores:

  ```
  docker-compose up --build -d
  ```

4. Una vez que los contenedores estén en funcionamiento, ejecuta el siguiente comando para acceder al contenedor del servidor web:

  ```
  docker compose exec web bash
  ```

5. Dentro del contenedor, ejecuta el siguiente comando para instalar las dependencias del proyecto:

  ```
  composer install
  ```

6. Sal del contenedor con ´exit´ y ejecuta los siguientes comandos para reiniciar el proyecto:

  ```
  docker compose down
  docker compose up -d
  ```
Con estos pasos, habrás descargado el código del proyecto, levantado los contenedores necesarios y instalado las dependencias. Ahora puedes comenzar a desarrollar en tu IDE. ¡Buena suerte!

### 1.2- Administración del sistema

Para implementar la base de datos en el adminer que usa el puerto 8080 y conectarte con localhost, sigue estos pasos:

1. Asegúrate de tener Adminer instalado en tu sistema. Puedes encontrar instrucciones de instalación en la documentación oficial de Adminer.

2. Abre tu navegador web y navega hasta `localhost:8080`.

3. Ingresa las siguientes credenciales de acceso a la base de datos:

  - Servidor: mysql
  - Usuario: toptap
  - Contraseña: abc123.

4. Realiza las copias de seguridad del sistema y de la base de datos según sea necesario (en config/sql tienes el archivo wingamesweb.sql que puedes importar directamente).

5. Gestiona los usuarios y la seguridad del sistema.

6. Gestiona las incidencias, tanto las relacionadas con el sistema como los fallos en el software.

Recuerda que estas tareas de administración del sistema deben realizarse una vez que el sistema esté en funcionamiento.

## 2- Manual de usuario

En esta sección se proporcionará información sobre cómo utilizar la aplicación informática. A continuación se detallan los pasos para registrarse, iniciar sesión y navegar por la aplicación:

1. **Registro de usuario:**
  - Haz clic en el enlace "Registrarse" en la barra de navegación.
  - Completa el formulario de registro con tu nombre, dirección de correo electrónico y contraseña.
  - Haz clic en el botón "Register" para crear tu cuenta.

2. **Inicio de sesión:**
  - Haz clic en el enlace "Iniciar sesión" en la barra de navegación.
  - Ingresa tu dirección de correo electrónico y contraseña.
  - Haz clic en el botón de envío para acceder a tu cuenta.

3. **Navegación por la aplicación:**
  - En la página principal, encontrarás opciones para ver la lista de scores, juegos y otras secciones relevantes.
  - Para jugar, simplemente haz clic en la pantalla para interactuar con el juego.
  - Explora las diferentes secciones de la aplicación utilizando los enlaces y botones correspondientes.

Una vez iniciada sesión, podrás acceder a las siguientes opciones adicionales en tu perfil:

- **Profile:** Aquí podrás ver información sobre el jugador y sus scores.
- **Edit profile:** Podrás realizar cambios en tu perfil.
- **Logout:** Para finalizar tu sesión en la aplicación.

Recuerda que estas opciones estarán disponibles una vez que hayas iniciado sesión en la aplicación.


## 3- Mejoras futuras

En este apartado se incluirán las posibilidades de mejora de la aplicación en el futuro. Algunas ideas para mejorar la aplicación podrían ser:

1. Mejoras de seguridad: Implementar medidas adicionales de seguridad, como autenticación de dos factores, encriptación de datos sensibles y auditorías de seguridad regulares.

2. Integración de pagos con wallets cripto: Permitir a los usuarios realizar pagos utilizando criptomonedas como Bitcoin o Ethereum, brindando una opción adicional de pago segura y descentralizada.

3. Funcionalidad de recuperación de contraseña: Agregar la capacidad para que los usuarios recuperen sus contraseñas en caso de olvido, a través de un proceso de restablecimiento de contraseña seguro y verificado.

4. Mejoras en la plataforma: Continuar mejorando la interfaz de usuario, la experiencia del usuario y la usabilidad de la aplicación en general. Esto puede incluir optimizaciones de rendimiento, mejoras en la navegación y la incorporación de nuevas funcionalidades solicitadas por los usuarios.

Recordar que estas son solo algunas ideas de posibles mejoras futuras. El objetivo es seguir evolucionando la aplicación para brindar una experiencia cada vez mejor a los usuarios.
