# 🗳️ Elections Page

## 📋 Overview

Elections Page es una plataforma web diseñada para facilitar la promoción, gestión y seguimiento de las campañas políticas de un partido o coalición. El proyecto está dividido en dos partes principales: una sección pública que permite a los ciudadanos informarse sobre los candidatos, eventos y propuestas del partido, y una sección administrativa que ofrece a los gestores herramientas para administrar el contenido de la página de forma eficiente y segura.

En la parte pública, los usuarios pueden explorar las diferentes propuestas políticas, conocer los perfiles de los candidatos y participar en encuestas o sugerencias. Además, la plataforma incluye un sistema de noticias y eventos, que mantiene a los ciudadanos actualizados sobre las actividades más relevantes.

En la parte administrativa, los responsables del sitio tienen acceso a un panel de control donde pueden gestionar candidatos, propuestas, noticias y eventos, así como personalizar el contenido del sitio web. Elections Page también ofrece funcionalidades de estadísticas y encuestas, lo que permite visualizar el nivel de aceptación de diferentes iniciativas.

El objetivo de Elections Page es proporcionar una solución digital moderna, segura y adaptable a cualquier contexto político, promoviendo la transparencia y la interacción entre los partidos políticos y la ciudadanía.

---

## 🌐 Features

### **Front (Público General)**

- **Inicio:**
  - Muestra el slogan del partido, logo y representante principal.
  - Incluye la misión, visión y valores del partido.
  - Presenta las personas que apoyan la candidatura.
  - Muestra las principales propuestas políticas.
  - Resalta los próximos eventos y noticias relevantes.
  - ![Inicio](screenshots/front_inicio.png)

- **Candidatos:**
  - Lista de candidatos con nombre, descripción breve y enlace a una página de detalles.
  - Muestra información clave de cada candidato, incluyendo su trayectoria y propuestas.
  - ![Candidatos](screenshots/front_candidatos.png)

- **Eventos:**
  - Calendario de eventos del partido.
  - Filtrado por etiquetas, fechas y nombres de eventos.
  - ![Eventos](screenshots/front_eventos.png)

- **Noticias:**
  - Sección de noticias relevantes, con posibilidad de filtrado y búsqueda.
  - ![Noticias](screenshots/front_noticias.png)

- **Propuestas:**
  - Lista de propuestas del partido, con posibilidad de votación y comentarios.
  - ![Propuestas](screenshots/front_propuestas.png)

- **Sugerencias:**
  - Formulario que permite a los ciudadanos enviar sus sugerencias, opiniones o preguntas.
  - ![Sugerencias](screenshots/front_sugerencias.png)

- **Estadísticas:**
  - Visualización de datos de encuestas y votaciones.
  - ![Estadísticas](screenshots/front_estadisticas.png)

---

### 🔐 **Back (Administradores)**

- **Login:**
  - Acceso seguro para los administradores del sitio mediante correo electrónico y contraseña.
  - ![Login](screenshots/back_login.png)

- **Perfil:**
  - Opciones para actualizar la información personal del administrador, como nombre, correo y contraseña.
  - ![Perfil](screenshots/back_perfil.png)

- **Home:**
  - Gestión del contenido visible en la página de inicio, como el slogan, logo y redes sociales.
  - ![Home](screenshots/back_home.png)

- **Usuarios:**
  - Gestión de cuentas de administradores, permitiendo la creación, edición y eliminación de usuarios.
  - ![Usuarios](screenshots/back_usuarios.png)

- **Propuestas:**
  - Gestión de propuestas políticas, permitiendo su creación, edición y eliminación.
  - ![Propuestas](screenshots/back_propuestas.png)

- **Noticias y Eventos:**
  - Gestión de las publicaciones de noticias y eventos del partido.
  - ![Noticias y Eventos](screenshots/back_noticias_eventos.png)

---

## ⚙️ Requirements

- **PHP**: Versión 8.0 o superior.
- **Laravel**: Versión 10.
- **MySQL**: Versión 8.0.
- **Servidor web**: Apache o Nginx.
- **Composer**: Para gestionar las dependencias de PHP.
- **Node.js**: Para gestionar las dependencias del front-end.

---

## 📦 Dependencias

- **Laravel**: Framework de desarrollo web en PHP.
- **Blade**: Motor de plantillas nativo de Laravel.
- **Axios**: Biblioteca para manejar solicitudes HTTP.
- **Posion Template**: Plantilla HTML5/CSS utilizada en el front-end.
- **Laravel UI**: Scaffolding para autenticación en Laravel.

---

## 📥 Instalación

Clonar el repositorio:

```bash
https://github.com/ArielParedesLozada/manejo-proyecto.git
```

Acceder al directorio del proyecto:

```bash
cd manejo-proyecto.git
```

Instalar las dependencias de PHP:

```bash
composer install
```

Instalar las dependencias de Node.js:

```bash
npm install
```

Configurar el archivo `.env` con los datos de conexión a la base de datos.

Generar la clave de la aplicación:

```bash
php artisan key:generate
```

Ejecutar las migraciones e implantación de la base de datos:

```bash
php artisan migrate:fresh --seed
```

Iniciar el servidor local:

```bash
php artisan serve
```

Acceder a la aplicación:

- Front: [http://localhost:8000](http://localhost:8000)
- Back (Admin): [http://127.0.0.1:8000/admin/organization/show-config](http://127.0.0.1:8000/admin/organization/show-config)

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT.
