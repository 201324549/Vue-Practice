<template>
    <div>
      <h1>This is Home Page</h1>
      <form action="">
        <inputField v-model="name" />
        <br>
        <button>Submit</button>
      </form>
      {{ name }}
      
    </div>
</template>

<script>
import InputField from '@/components/InputField.vue';
export default {
  components: {
    InputField,
  },

  data() {
    return {
      name: ''
    }
  },
}
</script>

<style scoped>
h1 {
  color: red;
}
</style>