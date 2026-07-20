# ⏱️ Cronómetro Digital

Cronómetro digital para medir intervalos de tiempo con controles de inicio, pausa y reinicio, diseño responsive y una experiencia visual compacta.

<img alt="Cronómetro Digital" src="https://github.com/micazoyolli/cronometro/blob/main/public/assets/screenshot.png" width="300" />

## 🌐 Demo

[Cronómetro Digital Demo](https://micazoyolli.github.io/cronometro/)

## 🛠️ Tecnologías

- HTML5
- JavaScript
- SCSS
- Vite
- Node 24
- Micazoyolli Foundation para SEO/build y reduced motion

## 📦 Instalación

```bash
yarn install
```

## 🚀 Scripts

```bash
yarn dev
yarn lint
yarn build
yarn preview
yarn deploy
```

Abre `http://localhost:5173/cronometro/` para ver la aplicación en local.

## 🗂️ Estructura del proyecto

```txt
public/
scripts/
src/
├── styles/
└── main.js
```

## 🚢 Despliegue en GitHub Pages

Este proyecto se publica en GitHub Pages desde la rama `gh-pages`. El comando `yarn deploy` compila la aplicación, limpia archivos `.DS_Store` del build y publica `dist/` usando el CLI de Micazoyolli Foundation sin crear commits de despliegue en `main`.

La configuración `base` de Vite debe conservar la subruta del repositorio: `/cronometro/`.

## 🧠 Funcionalidad

- Controles de inicio, pausa y reinicio.
- Animación de cronómetro tipo reloj.
- Interfaz responsive y accesible.

## 🧩 Construido con Micazoyolli Foundation

Este proyecto utiliza [Micazoyolli Foundation](https://github.com/micazoyolli/foundation) como infraestructura compartida. Las mejoras de tooling, estructura y despliegue deben realizarse en Foundation para beneficiar a todos los proyectos que la consumen.

## 👩‍💻 Autora

Una creación de [`<micazoyolli />✨`](https://nadia.dev)
