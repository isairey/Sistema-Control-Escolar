# 🎓 Control Escolar - Sistema Académico

Sistema web desarrollado para la gestión de procesos académicos y administrativos dentro de instituciones educativas. Este proyecto integra **Laravel (backend)** y **Vue.js (frontend)** para ofrecer una experiencia moderna, dinámica y escalable.

---

## 📌 Descripción

**Control Escolar** es una plataforma diseñada para centralizar la administración educativa, permitiendo gestionar alumnos, docentes, programas académicos y evaluaciones de manera eficiente.

El sistema está enfocado en proyectos académicos como los pertenecientes a **Agenda Ambiental**, considerando múltiples roles de usuario y vistas dinámicas según permisos.

---

## 🚀 Características

- 📋 Gestión de alumnos
- 👨‍🏫 Administración de docentes
- 📚 Control de programas académicos
- 🧾 Evaluaciones y seguimiento académico
- 🔐 Sistema de autenticación y roles
- 🔍 Búsqueda y filtrado dinámico
- ⚡ Interfaz reactiva con Vue.js
- 📊 Panel administrativo

---

## 🛠️ Tecnologías utilizadas

### Backend
- **Laravel** → Framework PHP
- **PHP 7.4+** → Lógica del servidor
- **MySQL** → Base de datos

### Frontend
- **Vue.js** → Interfaz reactiva
- **JavaScript (ES6+)** → Funcionalidad
- **HTML5 & CSS3** → Estructura y estilos

### Herramientas
- **Node.js & NPM**
- **Composer**
- **Git**

---

## 📂 Estructura del proyecto


📁 control-escolar
├── 📁 app
│ ├── 📁 Models
│ ├── 📁 Http/Controllers
├── 📁 resources
│ ├── 📁 js (Vue components)
│ ├── 📁 views
├── 📁 routes
│ └── web.php
├── 📁 public
├── 📁 database
│ ├── 📁 migrations
│ ├── 📁 seeders
└── README.md


---

## ⚙️ Requisitos

Antes de instalar el proyecto, asegúrate de tener:

- Node.js (recomendado con NVM)
- Composer
- PHP 7.4.x
- MySQL
- Git

> 💡 Opcional: Laragon (facilita el entorno en Windows)

---

## 🔧 Instalación

1. Clonar el repositorio:
```bash
git clone https://github.com/tuusuario/control-escolar.git
```
Entrar al proyecto:
```
cd control-escolar
```
Instalar dependencias de backend:
```
composer install
```
Instalar dependencias de frontend:
```
npm install
```
Configurar entorno:
```
cp .env.example .env
```
Generar clave:
```
php artisan key:generate
```
Configurar base de datos en .env
Ejecutar migraciones:
```
php artisan migrate --seed
```
Crear enlace de storage:
```
php artisan storage:link
```
## ▶️ Ejecución del proyecto

Ejecuta ambos procesos:
```
npm run dev
php artisan serve
```
El sistema estará disponible en:
```
http://127.0.0.1:8000
```
---
## 💡 Notas importantes
Asegúrate de tener correctamente configurado el archivo .env
Si hay errores de dependencias:
composer dump-autoload
php artisan optimize
Para reiniciar base de datos:
php artisan migrate:fresh --seed
---
## 🎨 Interfaz

- UI moderna basada en componentes Vue
- Navegación dinámica sin recargas
- Experiencia de usuario fluida
---
## 📈 Mejoras futuras
- 📱 Versión móvil (PWA)
- 🔔 Notificaciones en tiempo real
- 📊 Reportes avanzados
- 🧑‍💻 Sistema de permisos más robusto
- ☁️ Integración con servicios cloud
---
## 👨‍💻 Autor

Desarrollado por Isai Reyes Peña
---
## 📄 Licencia

MIT.
