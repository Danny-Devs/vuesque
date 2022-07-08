# vuesque

This slim, futuristic Vue 3 template provides you with hand-picked web development toolbox. It's great for beginners to start building with right away. 

In addition to a blank or skeleton Vue 3 project, this toolbox contains:

## added 1st-party tooling:

- Vue router -- This is optional in a Vue project, but it's necessary for websites with more than URL, or page).

Note: file-based routing, which is considered more intuitive by some, was not included, because I believe knowing both ways of doing things is valuable. If you want, you can add file-based routing; see Anthony Fu's Vitesse template, which contains file-based routing plus many other features (https://github.com/antfu/vitesse). Warning: Vitesse has so many features that Ant created a Vitesse-lite  version (https://github.com/antfu/vitesse-lite). 

- Pinia store (Vue's latest recommendation) -- Pinia provides a centralized location where you can manage your global reactive stores. Even if you think an external store is unnecessary, Pinia works with Chrome DevTools to provide improved debugging.

## CSS/UI tooling
- TailwindCSS (atomic/utility CSS framework) -- Vanilla CSS is already built-in to Vue. Tailwind provides a very different way to do CSS. Once you get the hang of it, you may find that it often saves you time while still providing excellent control and power. 
- DaisyUI -- Because I like Tailwind so much, I heard of DaisyUI, a free, open-source UI component library. It contains everything from buttons and modals to navbars and pagination. Simply put, it will probably save you time to select pre-built components from a well-designed component library than to build every single one of your components by hand. 

## additional features:

- Vuesque automatically imports the Vue components that you use, so you don't have to import them by hand. A little bit of syntactic sugar. This was done via Ant Fu's unplugin-vue-components (https://github.com/antfu/unplugin-vue-components).

- I've included vueUse, a powerful set of utility composables. Don't worry, your final build will only include the vueUse composables that you actually use. Check them out at www.vueuse.org.

## what's NOT in Vuesque:

- I HAVE NOT included any icon sets. A general rule to keep things small is to treeshake everything that you can. Entire icon sets/libraries can be very large. Maybe just throw in a handful of SVGs. Make sure that your final build contains only the icons that you're using. Ant Fu created Icones, which collects a bunch of open source icon sets and lets your search across them all (https://icones.js.org/). At the bottom you can copy the icon SVG or even a Vue component version.

Hopefully, this Vue 3 starter template will save you a lot of time when you're starting out on a new project.

Last updated 7/08/2022.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.vscode-typescript-vue-plugin).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```
