# vuesque

This slim, futuristic Vue 3 template provides you with:

a blank template:

- No need for you to manually delete a whole bunch of code and files.

core tooling:

- Vue router -- file-based routing was not included, because I believe it's important to know both ways. You can easily add file-based routing; Anthony Fu's Vitesse template contains file-based routing plus many other features (https://github.com/antfu/vitesse)
- Vue store (Pinia, the latest recommended version) -- Even if you don't need an external store because you're comfortable using Vue's built-in store capability, Pinia in integrated with Chrome DevTools to provide increased debugging capabilities.
- Tailwind (atomic/utility CSS framework) -- Once you get the hang of Tailwind, you miss it when it's not there. It's also dead simple to use vanilla CSS in Vue. If you want UI components, you'll have to install them onto this template.

additional features:

- reactivity transform is turned on, a piece of syntax sugar meaning you don't have to type '.value' over and over again in your script tags. (That option was turned on in the vite.config.js file)

- It also automatically imports the components that you use, so you don't have to import them by hand. More syntactic sugar.

- I've included vueUse, a powerful set of composable utility components. Don't worry, your final build will only include the vueUse components that you actually use. Check them out at www.vueuse.org.

what's NOT in Vuesque:

- I HAVE NOT included a UI library, because there are so many choices. I'll leave installing a UI library to you! (Tailwind is considered more of a UI utility library--it operates at a lower, or more atomic, level than higher level UI libraries that come with components like modals, navigation, and forms.)

- I HAVE NOT included any icon sets. A general rule to keep things small is to treeshake everything that you can. Entire icon sets/libraries can be very large. Make sure that your final build contains only the icons that you're using.

Hopefully, this Vue 3 starter template will save you a lot of time when you're starting out on a new project.

Last updated 6/28/2022.

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
