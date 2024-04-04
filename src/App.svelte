<script>
  import Fun from './Components/Fun.svelte';
  import ColorPicker from './Components/ColorPicker.svelte';
  let favoriteColor = 'red';
  let name = "";
  let isDisabled = false;
</script>

<div>
  <h1>Hello there, <span style="color: {favoriteColor}">{name}!</span></h1>
  <div>
    <Fun fontSize={40} />
    <input type="text" placeholder="Enter your name" bind:value={name}/>
    <button disabled={isDisabled}>Click Me</button>
  </div>
  <ColorPicker/>
</div>
