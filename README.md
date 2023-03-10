<!-- <p align='center'>
  <img src='https://user-images.githubusercontent.com/11247099/111864893-a457fd00-899e-11eb-9f05-f4b88987541d.png' alt='Vitesse - Opinionated Vite Starter Template' width='600'/>
</p> -->

<h2 align='center'>
<b>Lightweight version of <a href="https://github.com/antfu/vitesse">Vitesse</a></b>
</h2>

<h3 align='center'>
<a href="https://zafaralam-vue-starter.netlify.app/">Live Demo</a>
</h3>

## Features

- β‘οΈ [Vue 3](https://github.com/vuejs/core), [Vite 3](https://github.com/vitejs/vite), [pnpm](https://pnpm.io/), [ESBuild](https://github.com/evanw/esbuild) - born with fastness

- π [File based routing](./src/pages)

- π¦ [Components auto importing](./src/components)

- π [State Management via Pinia](https://pinia.vuejs.org/)

- π [Layout system](./src/layouts)

- π¨ [UnoCSS](https://github.com/antfu/unocss) - The instant on-demand atomic CSS engine.

- π Use icons from any icon sets in [Pure CSS](https://github.com/antfu/unocss/tree/main/packages/preset-icons)

- π₯ Use the [new `<script setup>` style](https://github.com/vuejs/rfcs/pull/227)

- β Use [Vitest](http://vitest.dev/) for unit and components testing

- π¦Ύ TypeScript, of course

- βοΈ Deploy on Netlify, zero-config

<br>

See [Vitesse](https://github.com/antfu/vitesse) for full featureset.

## Dropped Features from [Vitesse](https://github.com/antfu/vitesse)

- ~~i18n~~
- ~~SSG~~
- ~~PWA~~
- ~~Markdown~~

## Pre-packed

### UI Frameworks

- [UnoCSS](https://github.com/antfu/unocss) - The instant on-demand atomic CSS engine.

### Icons

- [Iconify](https://iconify.design) - use icons from any icon sets [πIcΓ΄nes](https://icones.netlify.app/)
- [Pure CSS Icons via UnoCSS](https://github.com/antfu/unocss/tree/main/packages/preset-icons)

### Plugins

- [Vue Router](https://github.com/vuejs/vue-router)
  - [`vite-plugin-pages`](https://github.com/hannoeru/vite-plugin-pages) - file system based routing
- [`unplugin-auto-import`](https://github.com/antfu/unplugin-auto-import) - Directly use Vue Composition API and others without importing
- [`unplugin-vue-components`](https://github.com/antfu/unplugin-vue-components) - components auto import
- [`unplugin-vue-macros`](https://github.com/sxzz/unplugin-vue-macros) - Explore and extend more macros and syntax sugar to Vue.
- [VueUse](https://github.com/antfu/vueuse) - collection of useful composition APIs

## Try it nowβ

### GitHub Template

[Create a repo from this template on GitHub](https://github.com/zafaralam/vue-starter-template/generate).

### Clone to local

If you prefer to do it manually with the cleaner git history

```bash
npx degit zafaralam/vue-starter-template my-vue-app
cd my-vue-app
pnpm i # If you don't have pnpm installed, run: npm install -g pnpm
```
