<template>
  <div id="todo-list">
    <form @submit.prevent="enviarFormulario">
      <div class="form-group">
        <input type="text" ref="name" />
        <input type="button" value="Add Task" />
      </div>
    </form>

    <table class="table">
      <thead>
        <tr>
          <th>ID</th>
          <th>Description</th>
          <th>Actions</th>
        </tr>
      </thead>
    </table>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
</style>
