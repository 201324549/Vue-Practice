<template>
    <div>
      <h1>This is Home Page</h1>
      <p>{{ name }}</p>
      <KossieCoder title="home title"/>
    </div>
</template>

<script>
import KossieCoder from '@/components/KossieCoder.vue';
export default {
  components: {
    KossieCoder
  },
  data() {
    return {
      name: 'Kossie Coder'
    }
  }
}
</script>

<style scoped>
h1 {
  color: red;
}
</style>