# vue-cli-plugin-pure-auth

Django Rest Framework Auth Plugin for [vue-cli@3.0](https://github.com/vuejs/vue-cli)

## Install

If you haven't yet installed vue-cli 3, first follow the install instructions here: https://github.com/vuejs/vue-cli

**Tip**: If you don't want to overwrite your current vue-cli because you still need `vue init`, [then try this](https://cli.vuejs.org/guide/creating-a-project.html#pulling-2-x-templates-legacy).

Generate a project using vue-cli 3.0
```
vue create my-app
```

Before installing the pure-auth plugin, make sure to commit or stash your changes in case you need to revert

To install the pure-auth plugin...
```
cd my-app
vue add vuetify
vue add pure-auth
```

## Using with other plugins

### Electron

Just add [vue-cli-plugin-electron-builder](https://www.npmjs.com/package/vue-cli-plugin-electron-builder)

```
vue add electron-builder
vue add vuetify
vue add pure-auth
yarn serve:electron
```
