# 🛫 ACME AIR - Proyecto de Maquetación UI

## 📌 Descripción General

Este proyecto representa la renovación de la interfaz de usuario para la aplicación web móvil de la aerolínea **ACME AIR**, desarrollada utilizando únicamente **HTML5** y **CSS3**. El objetivo es replicar con precisión las vistas proporcionadas por el equipo de **Diseño UI/UX**, garantizando un diseño **responsivo**, una navegación intuitiva y una experiencia de usuario coherente en dispositivos móviles.

---

## 🎯 Objetivos del Proyecto

- ✅ Reproducir fielmente los diseños gráficos suministrados.
- ✅ Garantizar una experiencia responsiva en distintos tamaños de pantalla (orientado a móvil).
- ✅ Implementar navegación funcional entre páginas mediante botones y enlaces.
- ✅ Mantener un código limpio, organizado y escalable para futuras integraciones.

---

## 🧩 Alcance del Proyecto

El proyecto incluye el desarrollo completo de las siguientes pantallas:

| Vista                    | Descripción                        |
| ------------------------ | ---------------------------------- |
| `login.html`             | Pantalla de inicio de sesión       |
| `register.html`          | Registro de nuevos usuarios        |
| `forgot-password.html`   | Recuperación de contraseña         |
| `set-password.html`      | Establecer nueva contraseña        |
| `menu.html`              | Menú principal tras iniciar sesión |
| `flight-search.html`     | Búsqueda de vuelos                 |
| `available-flights.html` | Lista de vuelos disponibles        |
| `check-in.html`          | Realizar check-in                  |
| `my-flights.html`        | Ver mis vuelos reservados          |

---

## 🗂️ Estructura del Proyecto

bash´´´

acme-air-ui/
│
├── css/ 🎨 Carpeta de estilos
│ ├── styles.css # Estilos globales y base
│ └── responsive.css # Media queries para adaptabilidad
│
├── images/ 🖼️ Recursos visuales utilizados (logos, iconos, etc.)
│ └── ...
│
├── pages/ 📄 Páginas HTML
│ ├── login.html # Iniciar sesión
│ ├── register.html # Registro de usuario
│ ├── forgot-password.html # Recuperar contraseña
│ ├── set-password.html # Crear nueva contraseña
│ ├── menu.html # Menú principal
│ ├── flight-search.html # Buscar vuelos
│ ├── available-flights.html # Vuelos disponibles
│ ├── check-in.html # Check-in
│ └── my-flights.html # Mis vuelos
│
├── index.html 🏠 Página inicial (redirige a login)
├── README.md 📝 Documentación del proyecto
└── LICENSE 🔐 Licencia MIT
´´´

---

## 🔧 Características Técnicas

### ✅ Diseño Responsivo

Todas las vistas están diseñadas para funcionar correctamente en dispositivos móviles, utilizando media queries y técnicas modernas de maquetación (Flexbox, Grid).

### 🧼 Código Limpio y Modular

- Uso de HTML semántico.
- Clases con nombres descriptivos y consistentes.
- CSS modularizado: estilos generales y específicos separados.

### 🌐 Navegación Funcional

Los botones y enlaces permiten navegar entre las diferentes vistas sin necesidad de lógica backend o JavaScript.

### 🖼️ Recursos Gráficos

Todas las imágenes e iconos han sido optimizados y organizados en la carpeta `/images`.

---

## 🧭 Mapa de Navegación

| Vista actual             | Botón / Enlace               | Vista destino            |
| ------------------------ | ---------------------------- | ------------------------ |
| Login                    | Ingresar                     | Menú ¿Qué quieres hacer? |
| Login                    | Crear cuenta                 | Registro                 |
| Login                    | ¿Has olvidado tu contraseña? | Recuperar contraseña     |
| Registro                 | Guardar                      | Crear Contraseña         |
| Recuperar contraseña     | Enviar                       | Crear Contraseña         |
| Crear contraseña         | Guardar                      | Menú ¿Qué quieres hacer? |
| Menú ¿Qué quieres hacer? | Cerrar sesión                | Login                    |
| Menú ¿Qué quieres hacer? | Buscar vuelos                | Búsqueda de vuelos       |
| Búsqueda de vuelos       | Buscar                       | Vuelos disponibles       |
| Vuelos disponibles       | Volver                       | Menú ¿Qué quieres hacer? |
| Menú ¿Qué quieres hacer? | Check In                     | Check In                 |
| Check In                 | Guardar                      | Menú ¿Qué quieres hacer? |
| Menú ¿Qué quieres hacer? | Mis vuelos                   | Mis Vuelos               |
| Mis Vuelos               | Volver                       | Menú ¿Qué quieres hacer? |

---

## 💻 Cómo Ejecutar el Proyecto

1. **Clona este repositorio:**
   bash´´´
   git clone https://github.com/JuanGualdronGallo1203/Project-H.C
