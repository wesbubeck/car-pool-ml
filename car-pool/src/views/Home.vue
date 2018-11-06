<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <CustomerInput/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import CustomerInput from "@/components/customerInput.vue";

export default {
    name: "home",
    components: {
            CustomerInput,
            HelloWorld
    }
};
</script>
