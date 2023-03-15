<script>
  const todoList = [
    'Get out of bed',
    'Make coffee',
    'Read feeds',
    'Have shower',
    'Brush teeth',
    'Get dressed',
    'Leave for work',
    'Get breakfast to go'
  ]
</script>


  <h1>Morning Todos</h1>
  <ol>
    {#each todoList as todoList  }
      <li><strong>{todoList}</strong></li>
    {/each}
  </ol>

