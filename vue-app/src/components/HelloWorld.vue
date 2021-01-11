<template>
  <h1>{{ msg }}</h1>
  <button @click="count++">count is: {{ count }}</button>
  <p>Edit <code>components/HelloWorld.vue</code> to test hot module replacement.</p>
  <List />
</template>

<script>
import List from './List.vue'

export default {
  name: 'HelloWorld',
  components: {
    List
  },
  props: {
    msg: String
  },
  data() {
    return {
      count: 0
    }
  }
}
</script>
