<script>
  import { page } from '$app/stores'
  
  console.log($page.params.sports);
</script>
<h1> Route params. Achievement-20</h1>
<p> Create a dynamic SvelteKit route that:</p>

<main>
  <h1>{$page.params.sports} </h1>

</main>