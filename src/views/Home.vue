<template>
  <div class="home">
    <Helloworld />
  </div>
</template>

<script>
// @ is an alias to /src
import Helloworld from '../components/helloworld.vue';
export default {
  name: "Home",
  components: {
    Helloworld
  },
};
</script>
