<template>
  <MainView msg="TarotKaka" />
 <Expense/>
</template>

<script>
import MainView from "./components/MainView.vue";
import Expense from "./components/Expense.vue";

export default {
  name: "App",
  components: {
    MainView,
    Expense
  },
};
</script>

<style>
@import "./assets/scss/main.scss";
</style>
