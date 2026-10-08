Hito 5 - Pizzería Mamma Mía 🍕

* Link Desafío: https://hito-5-pizzeria-mamma-4gsvssocm-study-latam.vercel.app/

* Este proyecto corresponde al Hito 5 de la Academia Desafío Latam, en el cual se implementa el sistema de enrutamiento del proyecto Pizzería Mamma Mía utilizando la librería React Router (v6+).

📋 Descripción del Proyecto

* En este hito se ha migrado la estructura de vistas a una arquitectura basada en páginas (pages) y se han configurado las rutas principales de la aplicación para navegación dinámica. Además, se han creado componentes específicos como Profile y NotFound (página 404), integrando la navegación desde un componente de encabezado (Navbar).

🚀 Requerimientos e Implementación

- Configuración de React Router.
- Instalación de react-router-dom.
- Encapsulamiento de la aplicación dentro de <BrowserRouter>.
- Reestructuración de Carpetas.
- Migración de los componentes principales a la carpeta src/pages:

Home
Register
Login
Cart
Pizza
Configuración de Rutas - Definición de las siguientes rutas principales:

/ ➡️ Muestra el componente Home.
/register ➡️ Muestra el componente Register.
/login ➡️ Muestra el componente Login.
/cart ➡️ Muestra el componente Cart.
/pizza/p001 ➡️ Muestra el componente Pizza.
/profile ➡️ Muestra el componente Profile.
/404 ➡️ Muestra el componente NotFound.
* ➡️ Captura cualquier ruta inexistente y redirige al componente NotFound.

Componente NotFound (404) (2 pts)
Página personalizada para errores 404.
Incluye un enlace que permite al usuario regresar a la ruta raíz /.
Componente Profile (1 pt)
Muestra la información de un usuario estático (email).
Incluye un botón para cerrar sesión (logout).
Componente Navbar (2 pts)
Implementación de enlaces de navegación mediante el componente de react-router-dom.
Redirección del botón "🛒 Total: $xxx" hacia la ruta /cart.

🛠️ Tecnologías Utilizadas
React (Vite / CRA)
React Router DOM
CSS / Bootstrap / Tailwind (según el framework UI configurado en el proyecto)

🔧 Instalación y Ejecución
Clonar el repositorio:
git clone 
cd pizzeria-mamma-mia


Instalar dependencias:
npm install


Ejecutar en entorno de desarrollo:
npm run dev


📂 Estructura del Proyecto
src/
├── components/
│   ├── Navbar.jsx
│   ├── Header.jsx
│   ├── CardPizza.jsx
│   └── Footer.jsx
├── pages/
│   ├── Home.jsx
│   ├── Register.jsx
│   ├── Login.jsx
│   ├── Cart.jsx
│   ├── Pizza.jsx
│   ├── Profile.jsx
│   └── NotFound.jsx
├── App.jsx
└── main.jsx

Marcelo Flores Fuentealba - 2026
