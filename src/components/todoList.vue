<template>
  <div>
      <input type="text" class="todo-input" placeholder="Write your todo">
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang="scss">
    .todo-input {
        width: 100%;
        padding: 10px 18px;
        font-size: 18px;
        margin-bottom: 16px;


        &:focus {
            outline: 0;
        }
    }
</style>
