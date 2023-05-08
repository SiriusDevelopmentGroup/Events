<script lang="ts">
  import Header from "./Header.svelte";
</script>

<Header />

<svelte:head>
  <title>Sirius Events</title>
  <link rel="icon" type="image/x-icon" href="/favicon.ico" />
</svelte:head>

<style lang="postcss">
  :global(html) {
    background-color: theme(colors.black);
    font-family: "SF UI Display", --apple-system, "Helvetica Neue", "Helvetica";
  }

  @font-face {
    font-family: "SF UI Display";
    src: url("https://fonts.cdnfonts.com/css/sf-ui-display");
    font-weight: 500;
  }
</style>
