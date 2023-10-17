<script>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
import MyHeader from "./components/MyHeader.vue";
import MyIntroduction from "./components/MyIntroduction.vue";
import MyCurrentStatus from "./components/MyCurrentStatus.vue";
import MyTechnologies from "./components/MyTechnologies.vue";
import MyFooter from "./components/MyFooter.vue";
export default {
  components: {
    MyHeader,
    MyIntroduction,
    MyCurrentStatus,
    MyTechnologies,
    MyFooter
  },
};
</script>

<template>
  <div id="app">
    <my-header></my-header>
    <my-introduction></my-introduction>
    <my-introduction></my-introduction>
    <my-current-status></my-current-status>
    <my-technologies></my-technologies>
    <my-footer></my-footer>
  </div>
</template>

