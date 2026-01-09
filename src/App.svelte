<script>
  import Header from './lib/Header.svelte'
  import SoulButton from './lib/SoulButton.svelte';
  import GreenBox from "./lib/GreenBox.svelte";
</script>

<Header />
<main>
  <h1 class="bold">The best way to make Deltarune fangames in Godot!</h1>

  <SoulButton>Determination.</SoulButton>
  <GreenBox />
</main>

<style>
  main {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 2rem;
    padding: 2rem;
  }
</style>
