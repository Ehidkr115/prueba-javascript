#  SPA Auth Guard con JavaScript Vanilla + Vite

Este proyecto es una **Single Page Application (SPA)** construida con **JavaScript Vanilla** y **Vite**. Incluye un sistema de autenticación básico con `localStorage`, rutas protegidas y carga dinámica de vistas HTML.

##  Características

-  Protección de rutas (Auth Guard)
-  Simulación de login (usuario y contraseña)
-  Carga de vistas externas (HTML) con `fetch()`
-  Lógica SPA sin frameworks


##  Estructura del proyecto

``` bash
    appVite/
    ├── assets/
    │    └── style.css
    ├── public/
    ├── src/
    │   ├── main.js
    │   ├── auth.js
    │   ├── router.js
    │   └── views/
    │       ├── 404.html
    │       ├──dashboard.html
    │       ├── home.html
    │       └──  login.html
    ├── index.html
    ├── package.json
    ├── .gitignore
    ├── README.md  # Este archivo
    └── vite.config.js
```





##  Rutas disponibles
- #/ → Página principal protegida

- #/dashboard → Dashboard privado

- #/login → Página de inicio de sesión


##  Requisitos
- Node.js >= 16

- Navegador moderno compatible con módulos ES
