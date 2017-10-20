<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>{{ "hello-essential-links" | format-message }}</h2>
    <ul>
      <li><a href="https://vuejs.org/v2/guide/" target="_blank">docs</a></li>
      <li><a href="http://vuejs-templates.github.io/webpack/" target="_blank">template-docs</a></li>
    </ul>
    <h2>{{ "hello-ecosystems" | format-message }}</h2>
    <ul>
      <li><a href="http://router.vuejs.org/" target="_blank">vue-router</a></li>
      <li><a href="http://vuex.vuejs.org/" target="_blank">vuex</a></li>
      <li><a href="http://vue-loader.vuejs.org/" target="_blank">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank">awesome-vue</a></li>
    </ul>
  </div>
</template>
<style lang="scss" src="./hello.scss" scoped></style>
