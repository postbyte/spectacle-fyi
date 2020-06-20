<script>
  import Header from "../components/Header.svelte";

  export let segment;
</script>

<style>

</style>

<main p="10 sm3">

  <main py="4">
    <slot />
  </main>

  <footer>
    <nav>
      <div>
        By <a href="https://github.com/postbyte">Postbyte Public Benefit Corporation</a>
        &copy; {new Date().getFullYear()}
      </div>
    </nav>
  </footer>
</main>