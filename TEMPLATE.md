- Run 'vue add vuex-module-generator' or 'vue invoke vuex-module-generator'
  - Prompts:
   - what is your store root directory?
   - what your module name is?
   * what is your root App.vue directory?
   * what is your root App.vue filename?
- generator index.js runs:
  - sets options constant
  - sets other path constants
  - checks if module exists
  - checks if root index.js store file exists
    - if not add the index.js file from template directory to files array
    * set boolean constant to trigger postProcessFiles to change root App.vue
  - add index, actions, mutations and getters files from template directory and add to files array
  - render files
  - edit root index.js store file
    - add 'import' line for new store file
    - add store file to 'modules' section
  - edit root app.vue if boolean above is true
    - modify\add 'import' line of root index.js file
    - remove default store.js file created by vue-cli-3
