<template>
  <div id="app">
    <Foo></Foo>
    <Bar></Bar>
  </div>
</template>

<script>
import Foo from './components/Foo.vue';
import Bar from './components/Bar.vue';

export default {
  beforeCreate () {
    console.log('App.vue beforeCreate11111111111');
  },

  created () {
    console.log('App.vue c1reated11111111111');
  },

  beforeMount () {
    console.log('App.vue beforeMount');
  },

  mounted () {
    console.log('App.vue mounted1');
  },

  components: {
    Foo, Bar
  }
}
</script>

