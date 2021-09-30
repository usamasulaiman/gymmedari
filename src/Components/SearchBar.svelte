<script>
  function searcher(e) {
    console.log('value is', e.target.value)
  }
</script>

<div class="search-bar container">
  <input autofocus type="search" on:input={searcher} placeholder="start typing question">
</div>

<style>
  :global(.container) {
    width: 90%;
    max-width: 500px;
    margin: 50px auto 0px;
  }
</style>