<template>
  <HelloWorld
  @updateName ="name => display(name)"
  />

</template>

<script setup>
      import HelloWorld from '@/components/HelloWorld.vue';

      const display = (name) => {
        console.log('App.vue : ' + name);
      }
</script>

<style scoped>

</style>
