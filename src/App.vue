<template>
  <div id="app">
    <Header />
    <SubHeader />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import SubHeader from './components/SubHeader.vue'

export default {
  name: 'App',
  components: {
    Header,
    SubHeader
  }
}
</script>

<style>
ul {
  list-style-type: disc;
  margin-block-start: 0px;
  margin-block-end: 0px;
  margin-inline-start: 0px;
  margin-inline-end: 0px;
  padding-inline-start: 0px;
}
li {
  list-style-type: none;
}
a {
  text-decoration: none
}
body {
  margin: 0px;
}
</style>
