<script>
  import Fun from './Components/Fun.svelte';
  let name = 'Bob';
  let favoriteColor = 'red';
</script>

<div>
  <h1>Hello there, <span style="color: {favoriteColor}">{name}!</span></h1>
  <div>
    <Fun fontSize={40} />
  </div>
</div>
