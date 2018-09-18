# vue-cli-plugin-modular-vuex

Create Modular Vuex stores for [vue-cli@3.0](https://github.com/vuejs/vue-cli)

## Install

If you haven't yet installed vue-cli 3, first follow the install instructions here: https://github.com/vuejs/vue-cli

**Tip**: If you don't want to overwrite your current vue-cli because you still need `vue init`, [then try this](https://cli.vuejs.org/guide/creating-a-project.html#pulling-2-x-templates-legacy).

Generate a project using vue-cli 3.0
```
vue create my-app
```

Before installing the modular-vuex plugin, make sure to commit or stash your changes in case you need to revert

To install the modular-vuex plugin...
```
cd my-app
vue add vuex
vue add modular-vuex
```

## Using with other plugins

### Electron - Vuetify

Just add [vue-cli-plugin-electron-builder](https://www.npmjs.com/package/vue-cli-plugin-electron-builder) and [vue-cli-plugin-vuetify](https://www.npmjs.com/package/vue-cli-plugin-vuetify)

```
vue add electron-builder
vue add vuetify
vue add modular-vuex
yarn serve:electron
```
