# ⏱️ Cronómetro Digital

Cronómetro digital moderno con diseño visual atractivo, ideal para medir intervalos de tiempo con precisión y estilo. Desarrollado con Vite y buenas prácticas.

<img alt="Cronómetro Digital" src="https://github.com/micazoyolli/cronometro/blob/main/public/assets/screenshot.png" width="300" />

## 🌐 Demo

[Cronómetro Digital Demo](https://micazoyolli.github.io/cronometro/)

## 🚀 Tecnologías usadas

- HTML5 + SCSS (con estructura modular)
- JavaScript moderno (ES6+)
- Vite 8
- Node 24
- @micazoyolli/foundation para SEO/build y reduced motion

## 📦 Estructura del proyecto

```
cronometro/
├── public/
│   ├── assets/
│   ├── icons/
│   ├── favicon.ico
│   ├── manifest.json
│   ├── meta.jpg
│   ├── robots.txt
│   └── sitemap.xml
├── src/
│   ├── main.js
│   └── styles/
│       ├── abstracts/
│       │   └── _variables.scss
│       ├── base/
│       │   ├── _animations.scss
│       │   ├── _fonts.scss
│       │   └── _reset.scss
│       └── components/
│       │   ├── _buttons.scss
│       │   ├── _clock.scss
│       │   ├── _footer.scss
│       │   ├── _numbers.scss
│       │   └── _timer.scss
│       └── layout/
│       │   └── _layout.scss
│       └── main.scss
├── .editorconfig
├── .gitignore
├── .nvmrc
├── LICENSE
├── index.html
├── package.json
└── vite.config.js
```

## ▶️ Uso

```bash
yarn install
yarn dev
yarn lint
yarn build
```

Abre ` http://localhost:5173/cronometro/` para ver la app en el navegador.

## 🧠 Funcionalidad

- Diseño visual minimalista
- Controles de inicio, pausa y reinicio
- Animación de cronómetro tipo reloj
- Totalmente responsive y accesible

---

## 👩‍💻 Autora

Una creación de [`<micazoyolli />✨`](https://nadia.dev)
