<script>
	import Button from "components/button.svelte";

  let count = 0;
</script>

<h2>Count: </h2>
<div id="count"> </div>
<Button> + 1 </Button>

<style>
  h2 {
    color: red;
  }
  #count {
    color: blue;
  }
</style>