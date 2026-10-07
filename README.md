# BookList SPA – Gestor de Libros Interactiva con Vue.js

Proyecto final del Módulo 6: Desarrollo de Interfaces Interactivas con Framework Vue.

## Objetivo
Desarrollar una SPA para Editorial Nova que permita registrar, visualizar, buscar, filtrar y eliminar libros, además de consultar el detalle de cada registro mediante rutas dinámicas.

## Tecnologías
- Vue 3
- Vue Router 4
- Vite
- HTML5, CSS3 y JavaScript ES Modules
- LocalStorage para persistencia local de los datos

## Estructura
```text
BookList/
├── index.html
├── package.json
├── vite.config.js
├── README.md
└── src/
    ├── App.vue
    ├── main.js
    ├── assets/main.css
    ├── components/Libro.vue
    ├── router/index.js
    └── views/
        ├── InicioView.vue
        ├── ListaLibros.vue
        └── DetalleLibro.vue
```

## Requerimientos implementados
- Componente principal `App.vue` con `template`, `script` y estructura de aplicación.
- Reactividad con `data`, `computed` y métodos.
- Patrón MVVM mediante separación de vista, estado y comportamiento.
- Componente reutilizable `Libro.vue`.
- Directivas `v-if`, `v-show`, `v-for`, `v-model` y `v-bind` mediante atributos reactivos.
- Formulario con `input`, `select` y `textarea`.
- Actualización del modelo en tiempo real y vista previa de los datos ingresados.
- Eventos `@click` y envío de formulario con `@submit.prevent`.
- Navegación con Vue Router.
- Rutas `/`, `/libros` y `/libros/:id`.
- Detalle mediante ruta dinámica y props.
- Búsqueda por título/autor y filtro por categoría.
- Eliminación de libros.
- Persistencia con LocalStorage.
- Diseño responsive para escritorio, tablet y móvil.

## Instalación y ejecución
Requiere Node.js instalado.

```bash
npm install
npm run dev
```

Luego abrir la dirección local indicada por Vite, normalmente `http://localhost:5173`.

Para generar la versión de producción:

```bash
npm run build
```

## Entregable
El proyecto se entrega como carpeta de código fuente lista para instalar dependencias y ejecutar.
