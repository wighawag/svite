<script lang="ts">
  import GrandChild from './GrandChild.svelte';
  import OtherGrandChild from './OtherGrandChild.svelte';
</script>

<style>
  * {
    color: deeppink;
  }
</style>

<div>
  <h2>Child 28</h2>

  <p>I have kids too:</p>

  <GrandChild />

  <OtherGrandChild />
</div>
