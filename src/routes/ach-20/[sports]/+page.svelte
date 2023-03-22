<h1>
  rashid 
</h1>

<script>
  import { page } from '$app/stores'

  console.log($page.params.sports);
</script>

<main>
  <h1>{$page.params.sports}:</h1>
</main>