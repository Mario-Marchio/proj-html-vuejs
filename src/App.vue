<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
export default {
  components: { AppHeader, AppMain, AppFooter },
  data() {
    return {
    }
  },
}
</script>

<template>
  <AppHeader />
  <AppMain />
  <AppFooter />
</template>

<style lang="scss">
.container-medium {
  margin: 0 auto;
  width: 900px;
}

.container-small {
  margin: 0 auto;
  width: 500px;
}

.rectangular-button {
  display: inline-block;
  padding: 10px 20px;
  background-color: #3bafbf;
  color: #fff;
  border: none;
  border-radius: 0;
}

.grey-line {

  background-color: #dddddd;
  width: 200px;
  height: 4px;
  margin-left: 150px
}
</style>
