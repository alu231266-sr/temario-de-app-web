# temario-de-app-web

## Propósito de Aprendizaje 1: Comprender los fundamentos del desarrollo de aplicaciones web

1.-Introducción al desarrollo web  
El desarrollo web implica crear sitios y aplicaciones accesibles desde navegadores.  
**Historia y evolución del desarrollo web:**  
La web inició con páginas estáticas (Web 1.0), evolucionó hacia la Web 2.0 (más interacción y contenido generado por usuarios) y actualmente permite aplicaciones complejas, interactivas y similares a apps nativas (SPA, PWA).  
**Tipos de aplicaciones web:**  
- Estáticas: Solo muestran información fija, sin interacción con bases de datos.
- Dinámicas: Generan contenido en tiempo real usando bases de datos.
- SPA (Single Page Application): Actualizan datos sin recargar la página.
- PWA (Progressive Web App): Funcionan offline, envían notificaciones y se pueden instalar como aplicaciones en dispositivos.

2.-Arquitectura de aplicaciones web  
**Cliente-Servidor:**  
El navegador (cliente) solicita información al servidor, que responde con datos y archivos.  
**Arquitectura de tres capas:**  
- Presentación: Interfaz gráfica (frontend).
- Lógica: Procesamiento y reglas de negocio (backend).
- Datos: Almacenamiento y acceso a la información (base de datos).  
**REST y API-first design:**  
REST define la comunicación entre sistemas usando HTTP y recursos identificados por URLs. API-first significa diseñar primero la API para asegurar la correcta interacción entre frontend y backend.

3.-Lenguajes y tecnologías fundamentales  
- **HTML:** Estructura la página web.
- **CSS:** Aplica estilos y diseño visual.
- **JavaScript:** Agrega interactividad y funcionalidad en el navegador.
- **PHP:** Procesa datos y lógica en el servidor.
- **MySQL:** Sistema de gestión de bases de datos relacional.

4.-Control de versiones  
**Git y GitHub:**  
Herramientas para gestionar los cambios en el código, colaborar y mantener historial de versiones.  
**Flujo de trabajo con ramas (branching, merge, pull requests):**  
Las ramas permiten desarrollar nuevas características de forma aislada. Se fusionan (merge) cuando están listas y se revisan mediante pull requests.

---

## Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web

1.-Diseño e implementación del frontend  
**Maquetación/Wireframe/Mockup:**  
Son bocetos y diseños previos que permiten planificar la interfaz gráfica.  
**API:**  
El frontend consume datos de una API para mostrar información dinámica y enviar datos al backend.

2.-Diseño e implementación del backend  
**Servidor:**  
Procesa las peticiones del cliente y ejecuta la lógica del sistema.  
**Manejo de peticiones y respuestas HTTP:**  
Utiliza métodos como GET, POST, PUT y DELETE para la comunicación entre cliente y servidor.  
**Conexión a bases de datos (MySQL, PostgreSQL, MongoDB):**  
Permite guardar, modificar y consultar datos almacenados.

3.-Bases de datos  
**Modelado de datos y relaciones:**  
Diseño eficiente de tablas y relaciones para representar la información correctamente.  
**ORM (Object Relational Mapping):**  
Herramientas que simplifican la interacción entre el código y la base de datos.  
**CRUD desde el backend:**  
Implementa operaciones básicas: Crear, Leer, Actualizar y Eliminar registros.

4.-Seguridad básica en aplicaciones web  
**Validación de formularios:**  
Previene errores y ataques verificando la información enviada por los usuarios.  
**Autenticación y autorización:**  
Controla el acceso a recursos y funcionalidades según la identidad y permisos del usuario.

---

## Propósito de Aprendizaje 3: Implementar y desplegar una aplicación web funcional

1.-Integración de frontend y backend  
**Interfaz de usuario Frontend:**  
Presenta los datos al usuario y permite la interacción.  
**Manejo de API:**  
Comunicación entre frontend y backend mediante peticiones HTTP (generalmente usando JSON).  
**Proceso de Solicitud y Respuesta de Backend:**  
El backend recibe peticiones, procesa la lógica y envía respuestas al frontend.

2.-Almacenamiento en Servidor  
**Tipos de servidores:**  
Dedicados, compartidos y en la nube (AWS, Azure, Google Cloud).  
**Servidores y servicios de hosting:**  
Plataformas para publicar aplicaciones web (Heroku, Netlify, Vercel, etc).  
**Proveedores de Servicios de Almacenamiento:**  
Servicios para almacenar archivos y bases de datos (Amazon S3, Firebase, etc).

3.-Optimización y rendimiento  
**Optimización de recursos (imágenes, scripts):**  
Reducción de tamaño de archivos, uso eficiente de imágenes y scripts para mejorar la velocidad.  
**Despliegue de aplicaciones web:**  
Publicación y configuración de la aplicación en servidores y dominios.  
**CI/CD básico:**  
Automatización de pruebas y despliegues usando herramientas como GitHub Actions.  
**Documentación del proyecto:**  
Guías y manuales que explican el uso y mantenimiento del sistema.
