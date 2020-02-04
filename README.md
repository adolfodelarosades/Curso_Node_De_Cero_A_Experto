# Node: De Cero A Experto

## Contenido del curso 230 clases 19:57:07

### Introducción 14:20

* Introducción 00:49
* ¿Cómo funciona el curso? 02:48
* Instalaciones necesarias 07:19
* ¿Cómo hacer preguntas?  03:24

### Fundamentos de Node 30:55

* Introducción a la sección 01:24
* Temas puntuales de la sección 00:11
* Preguntas comunes sobre Node 03:33
* Blocking vs Non Blocking I/O 06:18
* Hola Mundo en Node 05:20
* Ciclo de eventos de Node - Ejemplos 05:06
* Ciclo de vida de un proceso en Node 09:03

### Reforzamiento de los temas necesarios para seguir el curso 01:29:21

* Introducción a la sección 01:27
* Temas puntuales de la sección 00:11
* Nodemon 05:51
* Let vs Var 07:37
* Templates literales 04:21
* Destructuración de objetos 04:51
* Funciones de Flecha 08:19
* Callbacks 08:01
* Problemas comunes con los callbacks 13:50
* Promesas 11:24
* Promesas en cadena 03:22
* Async - Await 09:44
* Resolver problema de empleados/salarios con Async-Await 10:15
* Código fuente de la sección 00:08

### Bases de node 01:23:12

* Introducción a la sección 01:52
* Temas puntuales de la sección 00:06
* Inicio del proyecto - Sección 4 02:29
* Requerir paquetes - required 08:32
* Importar archivos de nuestro proyecto 11:29
* Recibir información desde línea de comando 08:57
* npm init - install - uninstall - package.json 09:47
* Yargs 10:04
* Ejecutar el comando: listar 09:43
* Optimizaciones para la configuración del Yargs 04:49
* Colores de la consola 05:12
* Respaldo del proyecto con GIT y GitHub 09:59
* Código fuente de la sección 00:13

### Aplicación de tareas por hacer 52:37

* Introducción a la sección 01:10
* Temas puntuales de la sección 00:08
* Inicio del proyecto - Por Hacer 05:40
* Validaciones automáticas con Yargs 07:32
* Crear una tarea persistente 07:55
* Leer información de un archivo JSON 05:54
* Comando para listar todas las tareas por hacer 04:14
* Actualizar una tarea por hacer 06:29
* Borrar tareas por hacer 05:45
* Optimizaciones para la aplicación de Notas 02:19
* Subir cambios a GitHub y tarea adicional 05:21
* Código fuente de la sección 00:09

### Aplicación del Clima - GeoLocation + Open Weather 46:38

* Introducción a la sección 01:36
* Temas puntuales de la sección 00:09
* Inicio del proyecto - Aplicación del Clima del Mundo 03:41
* Lectura - City-Geo-Location 00:16
* City-Geo-Location 02:23
* Peticiones HTTP - Axios - Request 09:27
* Optimizando el código para obtener la dirección y coordenadas 08:21
* Open Weather Map 10:41
* Conectando ambos servicios 04:55
* Subir a GitHub - Aplicación del Clima 04:54
* Código fuente de la sección 00:15

### Webserver - HTTP - EXPRESS - HBS 01:16:21

* Introducción a la sección 01:37
* Temas puntuales de la sección 00:06
* Inicio de proyecto - WebServer 08:25
* Introducción a EXPRESS 07:50
* Servir contenido estático 04:37
* Crear una pequeña página web 10:20
* Handlebars 07:38
* Usando parciales con HBS 13:18
* Usando helpers 07:46
* Heroku - Subiendo nuestra aplicación a producción 10:21
* Subir a GitHub los cambios - Webserver - Express- Heroku - HBS 04:18
* Código fuente de la sección 00:05

### REST Server - Configuraciones iniciales 50:57

* Introducción a la sección 02:03
* Temas puntuales de la sección 00:08
* Nota de actualización 00:11
* Instalación de MongoDB 05:31
* Robo 3T - Herramienta para manejar Mongo 03:44
* Iniciando el proyecto - RESTServer 04:43
* Peticiones HTTP - GET - PUT - POST - DELETE 09:47
* Códigos de respuestas HTTP 00:10
* Usando códigos de respuesta HTTP en Express 03:14
* Creando un archivo de configuración global 03:44
* Respaldo del RESTServer a GitHub 05:32
* Subir el RESTServer a Heroku 07:08
* Pro Tip: Ambiente de producción y desarrollo en Postman 04:50
* Código fuente de la sección 00:11

### Alcances del RESTServer y mantenimiento de la colección de usuarios 02:15:08

* Introducción a la sección 03:07
* Temas puntuales de la sección 00:15
* Alcances del proyecto - RESTServer 02:16
* Mongoose - Conectarnos a la base de datos 07:07
* Ordenar las rutas de Usuario 04:21
* Modelo de Usuario 07:17
* POST: Creando un usuario en la colección 09:18
* Validaciones personalizadas - email y role 08:16
* Nota de actualización - Bcrypt 00:14
* Bcrypt - Encriptando la contraseña 07:42
* PUT: Actualizar información del usuario 08:04
* Validaciones adicionales en el PUT 09:09
* GET: Obtener todos los usuarios de forma paginada 09:38
* Retornar número total de registros en una colección 02:41
* Filtrando los campos de los resultados de un get 01:35
* Delete: Borrando un usuario de la base de datos 06:45
* Delete: Marcar una eliminación en el mismo registro 05:37
* mLab: Un servicio de MongoDB en la nube 04:01
* MongoDB Atlas - Cloud Database - Configurar base de datos en la nube 06:13
* MongoDB Compass - UI para el manejo de MongoDB 04:55
* Actualizar todos los paquetes de mi aplicación de Node 04:49
* Conectar mLab o Mongo Atlas con nuestra aplicación de Node 06:36
* Nota de actualización 00:21
* Desplegando nuestro RESTServer en Heroku - Usuario 05:36
* Subir los cambios a GitHub - Usuario y RESTServer 03:03
* Variables de entorno personalizadas Heroku 05:56
* Código fuente de la sección 00:15

### Autenticación de usuario - JWT 01:23:16

* Introducción a la sección 01:45
* Temas puntuales de la sección 00:09
* Introducción a los Tokens 06:16
* Código para leer el payload y fecha de expiración de un Token - NO USAR 00:14
* Información importante sobre los JWT 09:04
* Ordenando las rutas en nuestro servidor 07:01
* Login de usuario 09:02
* Generar un JWT 0:22
* Proteger rutas mediante uso de Token - Middlewares 12:21
* Obtener información del Payload en cualquier servicio 06:15
* Middleware: Verificar Rol de administrador 07:46
* Pro Tip: Variables de entorno automáticas - Postman 06:58
* Desplegar en Heroku y backups en GitHub - Sección 10 05:49
* Código fuente de la sección 10 00:13

### Google Sign In - Front y BackEnd 49:44

* Introducción a la sección 01:17
* Temas puntuales de la sección 00:11
* Link para comenzar nuestra integración de Google Sign-In 00:09
* Obtención del API Key y API Secret de Google 11:49
* Validar Token de Google - Backend 11:06
* Crear un usuario personalizado en base a las credenciales de Google Vista previa 13:06
* Probar Google Sign-In desde Postman 03:43
* Pro Tip: Generar la documentación automática de nuestros servicios 03:54
* Publicar a Heroku y GitHub - Y pruebas en producción 04:19
* Código fuente de la sección 00:09

### Categorías y Productos 01:08:50

* Introducción a la sección 00:55
* Temas puntuales de la sección 00:04
* CRUD y rutas de Categorías 05:59
* Resolución de la tarea - CRUD y Rutas de Categorías 10:15
* Resolución de la tarea - CRUD y Rutas de Categorías - Parte 2 09:20
* Populate - Cargar información de otras tablas 04:08
* Modelo de Productos 00:06
* CRUD y Rutas Productos - Tarea 05:44
* Resolución de la tarea - CRUD y Rutas de Productos 10:23
* Resolución de la tarea - CRUD y Rutas de Productos - Parte 2 10:52
* Realizar búsquedas en base de datos 06:10
* Desplegar en Heroku y backups en GitHub - Sección 12 04:45
* Código fuente de la sección 00:08

### Carga de Archivos y protección de los mismos 01:19:28

* Introducción a la sección 01:23
* Temas puntuales de la sección 00:10
* Nota: sobre el fileupload-express 00:22
* Subir archivos a Express 11:54
* Validar la extensión del archivo a subir 06:54
* Ubicar y Renombrar archivos 08:31
* Actualizar imagen de usuario 07:17
* Borrar archivos del servidor 10:01
* Cargar imagen de productos - tarea 06:23
* Servicio para mostrar las imágenes 08:36
* Mostrar imagen de usuario o producto 06:45
* Middleware: Verificar token por url 05:58
* Desplegar en Heroku y backups en GitHub - Sección 13 05:00
* Código fuente de las sección 00:13

### Sockets - Fundamentos de los sockets 58:27

* Introducción a la sección 01:33
* Temas puntuales de la sección 00:11
* ¿Qué son los sockets y para qué nos pueden servir? 04:26
* Material de la sección 00:10
* Inicio del proyecto - Fundamentos sobre sockets 04:39
* Instalación de socket.io 05:38
* Configuración de socket.io - Front-End 05:27
* Detectar desconexiones de usuario o desconexiones del servidor 03:08
* Emitir desde el cliente - Escuchar en el servidor 07:07
* Emitir desde el servidor - Escuchar en el cliente 04:39
* Retroalimentación de emisiones del cliente hacia el servidor 04:11
* Ordenar el código del cliente y del servidor en archivos independientes 03:56
* Broadcast - Emitir a todos los usuarios 05:13
* Sockets a Heroku 05:53
* Subir a GitHub - Sockets Fundamentos 02:08
* Código fuente de la sección 00:07

### Sockets - Aplicación de Cola 01:31:22

* Introducción a la sección 02:17
* Temas puntuales de la sección 00:07
* Inicio de proyecto - Aplicación de Cola 05:09
* ES6 Classes - Clase para centralizar la lógica 11:07
* Lógica: Siguiente ticket y centralizar la grabación 03:17
* Socket: Siguiente Ticket 12:02
* Socket: Estado actual de la cola 05:03
* Colección de Tickets pendientes de atender 05:34
* Lógica: Atender un ticket 07:51
* Socket: Atender un Ticket 13:42
* Mostrar cola de tickets en pantalla 09:47
* Conectar la asignación de Tickets con la pantalla de cola 08:16
* Probar aplicación de Tickets en Heroku 04:36
* Subir a GitHub - Aplicación de colas 02:25
* Código fuente de la sección 00:08

### Socket Chat 01:51:21

* Introducción a la sección 02:01
* Temas puntuales de la sección 00:11
* Inicio del proyecto - Socket Chat 02:46
* Clase para controlar los usuarios del chat 10:32
* Front-End: Conectar un usuario 11:11
* Desconectar usuarios 08:07
* Enviando un mensaje a todo el grupo 08:04
* Enviar un mensaje a un usuario en específico 06:13
* Salas de Chat 07:58
* Mensajes y notificaciones a las salas de chat 08:31
* Respaldo a GitHub de nuestra aplicación de Chat 02:17
* Diseño de nuestra sala de chat 04:00
* Renderizar usuarios 09:54
* Obtener el ID del usuario conectado 03:00
* Enviar y renderizar mensajes 12:39
* Mejorar la forma de renderizar mensajes 10:32
* Propuestas para ejercicios del chat 01:07
* Subir cambios a GitHub - SocketChat 02:11
* Código fuente de la sección 00:07

### Bonus - Node + MySQL + TypeScript 01:12:11

* Temas puntuales de la sección 00:22
* Instalación necesaria 00:44
* Inicio de proyecto - TypeScript-MySQL 09:34
* Referencia al express básico - hecho en el curso 00:10
* Configurando express en TypeScript 11:55
* Desplegar el public folder 10:58
* Rutas de nuestra aplicación 05:00
* Crear base de datos en MySQL 05:42
* Paquete para conectarse a MySQL desde Node 00:09
* Clase para conectarse a MySQL 10:34
* Implementar patrón singleton y prevenir múltiples instancias de la clase 03:42
* Ejecutar queries en las rutas 12:58
* Más información sobre TypeScript 00:21

### Despedida del curso 03:30

* Más sobre mis cursos 00:33
* Cierre del curso 02:57
