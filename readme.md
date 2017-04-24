
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

**If you already have a `.sass-lint.yml` file, make sure there is the pattern** `'**/*.vue'` **in the `include` property.**
