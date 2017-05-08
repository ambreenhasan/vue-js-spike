<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <div>
      <Todo :options="tasks" v-model="task" placeholder="Task" style="width: 30%"/>
    </div>
  </div>
</template>

<script>
import vue from 'vue';
import Todo from 'todo-list-generator-ambreen'

vue.component('Todo', Todo);

export default {
  name: 'hello',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App',
      tasks: [ "task one", "task two", "task three", "learn vue.js"],
      task: ''
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
