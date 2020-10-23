<template>
  <div>
    <weatherComponent></weatherComponent>
  </div>
</template>

<script>
import './assets/tailwind.css'
import weatherComponent from '@/components/weatherComponent.vue';
export default {
  name: 'app',
  components: {
    weatherComponent
  }
}
</script>

<style>

</style>
