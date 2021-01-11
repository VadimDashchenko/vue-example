<template class="list-todo">
  <h2>Todos</h2>
  <ul v-for="todo in todos">
    <li>{{ todo.title }}</li>
    <li>{{todo.description}}</li>
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