<template>
  <div class="about">
    <h1>This is an about page</h1>
    <KossieCoder name = "hahaha hohohoh"/>
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
      title: 5
    }
  }
}
</script>