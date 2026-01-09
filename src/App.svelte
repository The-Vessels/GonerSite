<script>
  import Header from './lib/Header.svelte'
  import SoulButton from './lib/SoulButton.svelte';
  import GreenBox from "./lib/GreenBox.svelte";
</script>

<Header />
<main>
  <div class="bg"></div>
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
  .bg {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-image: url(src/assets/HIM.webp);
    background-repeat: no-repeat;
    background-size: cover;
    z-index: -1;
    opacity: 0.15;
  }
</style>
