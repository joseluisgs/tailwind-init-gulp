# Gulp con TailwindCSS Starter Kit

Gulp con TailwindCSS Starter Kit con el objetivo de crear páginas web estáticas usando [TailwindCSS](https://tailwindcss.com/) como Framework CSS. Incluye [Iconify](https://iconify.design/) como grupo de iconos. Además, puede usarse Sass para definir tus estilos con Tailwind. 


[![TailwindCSS](https://img.shields.io/badge/Tailwind%20CSS-Ready-06b6d4)](https://tailwindcss.com/)
[![Gulp](https://img.shields.io/badge/Gulp-%20Ready-cf4647)](https://gulpjs.com/)
[![Saas](https://img.shields.io/badge/Sass-%20Ready-ff69b4)](https://sass-lang.com/)
[![Licence](https://img.shields.io/github/license/joseluisgs/photo-gallery-ionic)](./LICENSE)
![GitHub](https://img.shields.io/github/last-commit/joseluisgs/tailwind-init-gulp)


![Portada](./src/img/cover.jpg)

- [Gulp con TailwindCSS Starter Kit](#gulp-con-tailwindcss-starter-kit)
  - [Uso](#uso)
  - [Configuración](#configuración)
  - [Autor](#autor)
    - [Contacto](#contacto)
  - [Licencia](#licencia)
      - [Agradecimientos](#agradecimientos)

## Uso

1. Instalar dependencias
```sh
npm install // or yarn install
```
2. Ejecutar modo desarrollo
```sh
npm run dev // or yarn dev
```
3. Generar ficheros de producción
```sh
npm run prod // or yarn prod
```

## Configuración


Puedes cambiar la configuración del proyecto desde el fichero **config.js**.
```js
{
  config: {
      ...
      port: 9050 // puerto de visualización
  },
  paths: {
     root: "./",
     src: {
        base: "./src",
        css: "./src/css",
        js: "./src/js",
        img: "./src/img"
     },
     dist: {
         base: "./dist",
         css: "./dist/css",
         js: "./dist/js",
         img: "./dist/img"
     },
     build: {
         base: "./build",
         css: "./build/css",
         js: "./build/js",
         img: "./build/img"
     }
  }
  ...
}
```
## Autor

Codificado con :sparkling_heart: por [José Luis González Sánchez](https://twitter.com/joseluisgonsan)

[![Twitter](https://img.shields.io/twitter/follow/joseluisgonsan?style=social)](https://twitter.com/joseluisgonsan)
[![GitHub](https://img.shields.io/github/followers/joseluisgs?style=social)](https://github.com/joseluisgs)

### Contacto
<p>
  Cualquier cosa que necesites házmelo saber por si puedo ayudarte 💬.
</p>
<p>
    <a href="https://twitter.com/joseluisgonsan" target="_blank">
        <img src="https://i.imgur.com/U4Uiaef.png" 
    height="30">
    </a> &nbsp;&nbsp;
    <a href="https://github.com/joseluisgs" target="_blank">
        <img src="https://cdn.iconscout.com/icon/free/png-256/github-153-675523.png" 
    height="30">
    </a> &nbsp;&nbsp;
    <a href="https://www.linkedin.com/in/joseluisgonsan" target="_blank">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/ca/LinkedIn_logo_initials.png/768px-LinkedIn_logo_initials.png" 
    height="30">
    </a>  &nbsp;&nbsp;
    <a href="https://joseluisgs.github.io/" target="_blank">
        <img src="https://joseluisgs.github.io/favicon.png" 
    height="30">
    </a>
</p>

## Licencia

Este proyecto esta licenciado bajo licencia **MIT**, si desea saber más, visite el fichero
[LICENSE](./LICENSE) para su uso docente y educativo.

#### Agradecimientos
Este proyecto está basado en el tutorial de [lazymozek](https://github.com/lazymozek/gulp-with-tailwindcss). Gracias por el contenido 🙂