<script>
  import Header from "../components/Header/index.svelte";
  import Footer from "../components/Footer/index.svelte";

  export let segment;
</script>

<style>
  main {
    position: relative;
    max-width: 56em;
    background-color: white;
    padding: 2em;
    margin: 0 auto;
    box-sizing: border-box;
  }
</style>

<Header {segment} />

<main>
  <slot />
</main>

<Footer />
