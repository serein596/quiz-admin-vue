<template>
  <div id="app">
    <!--<h1 id="htitle">{{ message }}</h1>-->
    <!--<test-button></test-button>-->
    <!-- <user-view></user-view> -->
    <!-- <question-view></question-view> -->
    <router-view></router-view>
  </div>
</template>

<script>
// import QuestionView from './views/elment/QuestionView.vue';
//import TestButton from './views/elment/TestButton.vue';
// import UserView from './views/elment/UserView.vue';

export default {
  // components: { QuestionView },
  data() {
    return {
      message: "hello vue",
     // num: 1,
    };
  },
  methods: {
  },
};
</script>


<style>
#htitle {
  color: red;
}
</style>