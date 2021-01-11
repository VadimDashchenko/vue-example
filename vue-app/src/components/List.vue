<template>
  <h2>Todos</h2>
  <ul>
<!--    <li v-for="todo in todos">{{ todo }}</li>-->
  </ul>
</template>

<script>
  export default {
    name: 'List',
    data(){
      return{
        todos: [
          {
            id: 1,
            title: 'Title',
            description: 'Description'
          },
          {
            id: 2,
            title: 'Title 2',
            description: 'Description'
          },
          {
            id: 3,
            title: 'Title 3',
            description: 'Description'
          }
        ]
      }
    }
  }
</script>