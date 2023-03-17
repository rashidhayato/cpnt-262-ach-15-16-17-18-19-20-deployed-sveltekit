
<script>
  let text = 'Click to sign up !';

  const changeText = function () {
    text = 'welcome to sign up page';
  }
</script>
<main>
  <div>
    <p>{text}</p>
    <button on:click={changeText}>Sign up!</button>
  </div>


</main>

<style>
  div {
    width: 30ch;
    border: 1px solid black;
    background-color: #eee;
    padding: 1rem;
    margin: auto;
  }

</style>





