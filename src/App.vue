<script setup>
// import HelloWorld from './components/HelloWorld.vue'
// import TheWelcome from './components/TheWelcome.vue'
</script>

<script>
export default {
  data() {
    return {
      numEmployees: 10,
    };
  },
  methods: {
    addEmployees() {
      this.numEmployees++;
    },
    subtractEmployees() {
      this.numEmployees--;
    },
    foo(){
      console.log("foo");
    }
  },
};
</script>


<template>
  <header>
    <!-- <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" /> -->

    <div class="wrapper">
      <HelloWorld msg="You did it!" />
    </div>
  </header>

  <main>
    <!-- <TheWelcome /> -->

    <div class="container-fluid">
      <h1>BOOTSTRAP</h1>
      <button class="btn btn-primary" @click="foo()">
        BUTTON
      </button>
    </div>

  </main>
</template>
