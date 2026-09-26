# Gothic II: New Balance · Wiki en español

Wiki estática en español del mod **Gothic II: New Balance**, traducida y reorganizada a partir de la documentación original en polaco.

## Contenido

- **Gremios** principales (Mago de Fuego, Mago de Agua, Nigromante, Paladín, Cazador de Dragones…) y **gremios secundarios** (asesinos, cazadores, comerciantes, ladrones).
- **Misiones** por capítulos (1 a 5) y misiones secundarias.
- **Tramas** y zonas nuevas del mod.
- **Configuración** del juego (`Gothic.ini`).

## Stack

Astro 6 · Tailwind CSS 4. Sitio 100 % estático: cada página es un fichero `.astro` en `src/pages/`, así que añadir contenido es crear una página.

## Desarrollo

```bash
pnpm install
pnpm dev       # http://localhost:4321
pnpm build     # genera ./dist
```

## Estructura

```text
src/pages/
├── gremios/              # un fichero por gremio
├── gremios-secundarios/
├── misiones/             # capitulo-1 … capitulo-5, secundarias
├── tramas/
└── configuracion/
```

---

Proyecto de fans sin ánimo de lucro. *Gothic* es una marca de sus respectivos propietarios.
