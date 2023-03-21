<script>
  import {todoList}from './app.js';
</script>


<main>
  <h1>Morning Todos</h1>
  <ol>
    {#each todoList as todo}
      <li>{todo}</li>
    {/each}
  </ol>
</main>