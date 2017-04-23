This linter plugin is a fork of [AtomLinter/linter-sass-lint](https://github.com/AtomLinter/linter-sass-lint) that provides an interface to [sass-lint](https://github.com/sasstools/sass-lint) for [Vue.js](https://vuejs.org).

It will parse **.vue** files with style tags and works for Sass or SCSS:

```html
<template>
<!-- your tamplate here -->
</template>

<script>
  export default {
    props: {
      // ...
    },
  };
</script>

<style lang="scss" scoped>
/* your rules here */
</style>
```

#### Plugin installation

`npm install lint-sass-vue`

#### .sass-lint.yml

A .sass-lint.yml config file is required for this linter. You can find an example of one [here](https://github.com/fsblemos/lint-sass-vue/blob/master/.sass-lint.yml).

**If you already have a `.sass-lint.yml` file, make sure there is the pattern** `'**/*.vue'` **in the `include` property.**
