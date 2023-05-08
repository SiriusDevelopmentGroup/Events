<script>
  import Header from "./Header.svelte";
</script>

<Header />

<svelte:head>
  <title>Sirius Events</title>
  <link rel="icon" type="image/x-icon" href="/favicon.ico" />
</svelte:head>

<style lang="postcss">
  :global(html) {
    background-color: theme(colors.blue.300);
  }
</style>
