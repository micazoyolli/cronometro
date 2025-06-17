# ⏱️ Cronómetro Digital

Cronómetro moderno con diseño visual atractivo, ideal para medir intervalos de tiempo con precisión y estilo. Proyecto desarrollado con Vite y buenas prácticas.

<img alt="Cronómetro Digital" src="https://github.com/micazoyolli/cronometro/blob/master/public/assets/screenshot.png" width="300" />

## 🌐 Demo

[Cronómetro Digital Demo](https://micazoyolli.github.io/cronometro/)

## 🚀 Tecnologías usadas

- HTML5 + SCSS (con estructura modular)
- JavaScript moderno (ES6+)
- Vite

## 📦 Estructura del proyecto

```
cronometro/
├── public/
│   ├── assets/
│   │   ├── favicon.ico
│   │   └── screenshot.png
│   ├── manifest.json
│   └── robots.txt
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
├── index.html
├── .editorconfig
├── .gitignore
├── .nvmrc
├── LICENSE
├── package.json
└── vite.config.js
```

## ▶️ Uso

```bash
yarn install
yarn dev
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
