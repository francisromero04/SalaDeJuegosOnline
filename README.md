# Sala de Juegos

## Descripción del Proyecto

La aplicación "Sala de Juegos" es una plataforma diseñada para que los usuarios puedan medir sus habilidades cognitivas y motrices a través de una serie de juegos. Los usuarios deben registrarse e iniciar sesión para acceder a los juegos y ver estadísticas de su desempeño.

## Componentes y Funcionalidades

### Sprint 1 (Clase 02)
- **Configuración del Proyecto:**
  - Creación del proyecto y despliegue en Heroku/Firebase.
- **Componentes Implementados:**
  - **Login:** Componente para que los usuarios se registren e inicien sesión.
  - **Home:** Pantalla principal con acceso a los juegos y listados.
  - **Quién Soy:** Información personal del alumno, imagen y explicación del juego propio.
- **Estilo:**
  - Inclusión de un favicon.

### Sprint 2 (Clase 03)
- **Home:**
  - Pantalla principal con acceso a juegos y listados.
  - Información del usuario logueado y opción de Logout.
- **Login:**
  - Validación del usuario con Firebase.
  - Registro de la fecha y hora de ingreso en Firebase.
  - Botones de acceso rápido para facilitar el login.
- **Registro:**
  - Creación de nuevos usuarios y redirección automática al Home.
  - Mensajes de error si el usuario ya está registrado (sin uso de alertas).

### Sprint 3 (Clase 04)
- **Chat:**
  - Integración de un chat accesible solo para usuarios logueados.
  - Registro del usuario y hora de los mensajes enviados.
- **Módulos y Lazy Loading:**
  - Implementación de módulos y carga diferida de componentes.
- **Juegos Implementados:**
  - **Ahorcado:** Juego con botones para ingresar letras en lugar de teclado.
  - **Mayor o Menor:** Juego de cartas donde el jugador adivina si la siguiente carta es mayor o menor.

### Sprint 4 (Clase 05)
- **Preguntados:**
  - Implementación del juego Preguntados con imágenes obtenidas de una API.
  - Integración del llamado a la API mediante un servicio.
  - Opciones de elección sin uso de teclado.
- **Juego Propio:**
  - Desarrollo e implementación de un juego original.
  - Descripción del juego propio en la sección “Quién Soy”.
