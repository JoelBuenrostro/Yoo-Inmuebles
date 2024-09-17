# Yoo Inmuebles

```sh
npm create astro@latest -- --template minimal
```

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/withastro/astro/tree/latest/examples/minimal)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/withastro/astro/tree/latest/examples/minimal)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/withastro/astro?devcontainer_path=.devcontainer/minimal/devcontainer.json)

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

## 🚀 Estructura del Proyecto

Dentro de tu proyecto Astro, verás las siguientes carpetas y archivos:

```text
/
├── public/
├── src/
│   └── pages/
│       └── index.astro
└── package.json
```

Astro busca archivos `.astro` o `.md` en el directorio `src/pages/`. Cada página se expone como una ruta basada en su nombre de archivo.

No hay nada especial acerca de `src/components/`, pero es donde nos gusta colocar cualquier componente de `Astro/React/Vue/Svelte/Preact`.

Cualquier recurso estático, como imágenes, se puede colocar en el directorio `public/`.

## 🧞 Comandos

Todos los comandos se ejecutan desde la raíz del proyecto, desde una terminal:

| Command                   | Action                                                      |
| :------------------------ | :---------------------------------------------------------- |
| `npm install`             | Instala dependencias                                        |
| `npm run dev`             | Inicia el servidor de desarrollo local en localhost:4321    |
| `npm run build`           | Compila tu sitio de producción en ./dist/                   |
| `npm run preview`         | Previsualiza tu compilación localmente, antes de desplegar  |
| `npm run astro ...`       | Ejecuta comandos CLI como astro add, astro check            |
| `npm run astro -- --help` | Obtén ayuda para usar el CLI de Astro                       |
